# Competitor gap check: VOS vs ninja-vapes.co.uk, vampirevape.co.uk, vapeshop.co.uk

Snapshot date: 2026-09-24. In-stock items only, on every side.

## What is in here

| File | What it lists |
|---|---|
| `summary.csv` | One row per competitor with the counts below. |
| `<site>_missing_products.csv` | Product lines the competitor has in stock that VOS does not sell (or has fully out of stock). One row per product line, with the in-stock flavours listed in a column. |
| `<site>_missing_variants.csv` | Products VOS does sell, where the competitor has an in-stock flavour / colour / strength / resistance that VOS does not have in stock. One row per missing variant. |
| `<site>_matched_products.csv` | Audit trail: which competitor product line was matched to which VOS product, with the match score. Use it to check a match before acting on a "missing variant" row. |

`<site>` is `ninja`, `vamp` or `vapeshop`.

## How to read the columns

**missing_products**
- `product`: the product line. Where a competitor lists every flavour as its own product (Vapeshop does this for pods and e-liquids), those listings are grouped into one line and `listings` says how many were grouped. `example_listing` shows one of the original titles.
- `in_stock_flavours` / `flavours_in_stock`: how many flavours the competitor has in stock for that line, and which.
- `other_variants_in_stock`: strengths, colours or resistances in stock.
- `closest_vos_product` / `closest_vos_score`: the nearest VOS product the matcher found but rejected (score below 0.60). Blank means nothing close. If the score is 0.45 to 0.59, check it by eye: it may be the same product under a different name or generation.

**missing_variants**
- `vos_status`: `not listed on VOS` means VOS has no such variant at all. `listed on VOS but out of stock` means VOS lists it but stock is 0 (a restock candidate rather than a new listing).
- `match_confidence`: `high` (score 0.85+), `medium` (0.70 to 0.84), `low` (0.60 to 0.69). Treat `low` rows as "check first".
- `variant_type`: `strength` and `resistance` rows only appear when the VOS product also has that option, so they are real gaps and not a labelling difference.

## Data sources

| Site | Source | Notes |
|---|---|---|
| VOS | Shopify Admin bulk export | Active, published products. A variant counts as in stock when Shopify says it is available for sale. |
| vapeshop.co.uk | Shopify `products.json` | Per-variant availability flag. |
| ninja-vapes.co.uk | Every product page from its sitemap (OpenCart) | Per-flavour stock comes from the page's variant data. Nicotine-pouch pages only expose strength radio buttons with no per-strength stock, so those use page-level stock. |
| vampirevape.co.uk | Every product page from its sitemap (Magento) | Per-option stock comes from the page's configurable-product `salable` map. |

## How the matching works (and where it can be wrong)

1. Titles are cleaned: marketing tails ("Only £8.99 | Any 3 for £24", "Best Price"), pack sizes and prices are stripped. Spelling is unified (Elfbar / Elf Bar, 10K / 10000, Pro Max+ / Pro Max Plus, Blue Razz / Blue Raspberry).
2. Each product is classified by type (kit, refill pods, nic salt, shortfill, coil, pouch, tank, ...). Products only match within the same type, so a device kit never matches its refill pods.
3. The brand is taken from the vendor field or the title.
4. Flavours and colours that sit inside a title ("Blue Razz Lemonade Hayati Pro Max Plus 6000 Refill Pods") are pulled out and treated as variants, so per-flavour listings group into one product line.
5. Lines are compared within the same brand and type on the remaining model words. Puff counts, bottle sizes and model numbers must agree: "XROS 5" will not match "XROS 3", and "Argus G3 Mini" will not match "Argus G2 Mini".
6. Variant values are compared after the same cleaning; "Banana Ice - 20mg Nicotine" equals "Banana Ice".

Known weak spots:
- A product VOS sells under a very different name will show up as a missing product. The `closest_vos_product` column is there to catch these.
- Where a competitor uses an odd flavour name the matcher could not recognise (mostly Vampire Vape's own e-liquid names), the flavour may stay inside the product name and appear as its own line instead of grouping.
- Pack sizes (1 pack vs 2 pack) are ignored on purpose, so a 2-pack on a competitor and a 1-pack on VOS count as the same product.
