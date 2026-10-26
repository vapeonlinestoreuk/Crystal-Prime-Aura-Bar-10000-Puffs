# Mango Vape (`mango-vape`) - report, 26 Oct 2026

**Target:** gid://shopify/Collection/459373740281, live, 84 lines (TITLE CONTAINS "mango" AND inventory > 0). Image present.
**Backup:** description empty, "nothing to back up"; old title + seo in `vos_backup.previous`.
**Title:** "Mango Vape Collection | Juice & Prefilled Vapes" changed to "Mango Vape UK | Kits, Prefilled Pods & Mango Vape Juice" (55 chars).

## Ahrefs truth (gb)
- **Primary:** "mango vape" 800/mo, KD 0, TP 300, AI Overview (GSC 243 impr, pos 36.5 on this handle). Slots: H1, intro bold, meta title, FAQ H2, closing H2.
- **Secondaries:** mango vape juice 400 (H1, meta, liquids H2, FAQ), mango ice vape 450 (H3 + FAQ; no in-stock seller has an ice finish, said plainly), mango e liquid 350 (liquids H2), mango disposable vape 150 (H3 + FAQ), mango lost mary 150, mango vape pods 80 (pods H2 + FAQ), mango elf bar and mango hayati (FAQs).
- **Siblings' heads out of H2s and meta:** triple mango vape 500 (triple-mango-flavour-vape, GSC pos 21.6) and peach mango vape 30 (peach-mango-vape, pos 10.3): one linked intro mention each.
- **SERP:** AI Overview, vapestore collection #2 (DR 59), vapeclub pods #4 (DR 70), then product pages. PAA used: "Is mango a good vape flavour?", "Is there a mango vape flavor?".
- **Units:** 836 + 594 + 1,280 + 0 = **2,710** (cap 3,500). Workspace counter 123,438 to 136,220.

## Cannibalisation verdict
Three mango collections, all published and empty before this run; this page owns mango vape / mango ice vape / mango vape juice, siblings keep triple mango and peach mango. Differentiated.

## Products featured (ShopifyQL net_items_sold, 120 days: 120 units across 19 ACTIVE in-stock sellers)
1 Triple Mango Bar Juice 5000 10ml (30), 2 Triple Mango Oxva Xlim pods (15), 3 Mango Elf Bar Elfa pods (15), 4 Cherry Ice / Peach Mango Hayati Pro Ultra Plus 25000 (10), 5 Pineapple Mango Orange Elf Bar Elfliq 10ml (8), 6 Triple Mango Hayati Pro Max 100ml (4; only shortfill that sold, kept for format coverage over the Hayati Pro Max 10ml at 7 and SKE Bar 600 at 6, both tabled). No kit-and-own-pods pair reached the cut (Hayati Pro Max Plus 6000 kit 4 + pods 3; both tabled). Tables: all 19 sellers, products.json.

## Metafields
`custom.description_above_collection` (117 words, above_collection.json), `custom.subcollections` (triple-mango-flavour-vape, peach-mango-vape, prefilled-vape-pods, pre-filled-pod-vape-kits, e-liquid, fruit-flavour-e-liquids; all published, subcollections.json), `vos_seo.description_log` (recheck 2026-11-23). All read back.

## Data problems
1. **Multipack compare-at prices copy the single figure** (compare below price) on Elf Bar Elfa, Elfa Pro and Mate P1 pods, Lost Mary BM6000 and Nera 30K, Hayati Pro Max Plus 6000 pods and every 10ml multipack. Hayati Pro Max 100ml: compare £7.99 on the £8.99 variant.
2. Pineapple Peach Mango SKE Bar 600 spec metafield says "Flavour: Peach Ice".
3. Hayati Pro Ultra Plus 25000 kit and Lost Mary Nera 30K: empty descriptionHtml. Bar Juice 5000 copy still says "4 for £10", "£3.49 single" and 10mg/20mg only.
4. Three mango products have one review each; the rest none. Trustpilot omitted.

**Specs:** all from VOS pages / spec metafields (Oxva and Elfa pod specs are VOS descriptionHtml, retailer-side).

## Length note
2,866 visible words against the 1,000 to 1,400 flavour target: the mandated blocks, tables, guide and ten FAQs cannot fit it. Raj to decide what to drop.

## Pushed and confirmed
collectionUpdate (descriptionHtml + seo + title) and metafieldsSet x3: no userErrors; title, meta title (56), meta description (154), HTML and all four metafields read back, six collection references resolve. Zero untitled links, zero em dashes, no compliance or ban text, every model name carries its brand.
