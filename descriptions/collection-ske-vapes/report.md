# SKE Vapes (collection) report, 26 Oct 2026

**Target:** gid://shopify/Collection/443752055033, `ske-vapes`, live, 109 products (rule TITLE CONTAINS "Ske" AND inventory > 0, untouched). Format and CSS copied from `wholesale-vapes`. Collection image present.
**Backup:** description was empty: `vos_backup.previous` = "nothing to back up" plus old seo and title, read back. **H1** changed from "Buy SKE Crystal Vape | All SKE Vape Flavours In Stock" to "SKE Vapes UK | SKE Crystal Kits, Refill Pods & Nic Salts" (56 chars). Handle unchanged.
**Raj's two mid-run rules applied before the final push:** no ban box, no June 2025 explainer, no "since the ban" framing anywhere (problem box, one guide H3 and the "Are SKE vapes illegal" FAQ deleted); every `<a>` carries a title, including all eight `vos-cta-button` links ("view ske crystal cl6000 replacement pods" style).

## Ahrefs truth (gb)
- **Primary:** ske vape 1,700/mo KD 3 (twin ske vapes 900). Only striking-distance term in GSC: 988 impressions, pos 14.8, 5 clicks. Slots: intro bold, H1, FAQ H2, CTA H2, meta title.
- **Secondaries, slots:** ske crystal 1,300 (H1, table H2s); ske crystal vape 5,800 (parent topic "crystal vape", used in intro only, not in H2 or meta: see cannibalisation); ske bar 1,200 / ske bar 600 500 (block H3, guide box, FAQ); ske 600 pro pods 1,400 / ske 600 pro 800 (block H3, FAQ); ske bar 15k 900 (block H3, guide box); ske crystal cl6000 800 (block H3, FAQ); ske crystal plus 700 / plus pods 450 / ske crystal 4 in 1 250 (compatibility H3); ske vape flavours 250 / ske crystal vape flavours 300 (flavours H3); ske 30k pro max 400 (table, guide box). FAQ questions from matching-terms: cl6000 how to use 200, ske bar how to refill 100, how long to charge 20, taste burnt 20, can you refill 10; PAA: are ske vapes good, can I refill a ske vape. PAA "Are SKE vapes illegal" and "Is SKE vape safe" left out (ban rule, no health claims).
- **SERP "ske vape":** #1 skebarvape.co.uk (brand), then vapeuk vendor page (DR 64), vapeclub, vapesuperstore, uk.skevape.com; AI Overview cites the brand site, Totally Wicked guide, vapeuk, vapeclub, vapesuperstore. All brand lists with no sales ranking or pod-compatibility table.
- **GSC (collection URL, GB, 90 days):** ske vape 988 impr / 5 clicks pos 14.8; ske crystal 378 pos 54; ske crystal vape 364 pos 36.8; ske crystal vapes 303 pos 29.6; ske 278; ske vapes 129; ske disposable vape 91. "ske vape" and "ske vapes" are in H1, intro and FAQ H2.
- **Units spent (my calls):** 792 + 880 + 525 + 496 = 2,693 of the 3,500 cap. Workspace counter 111,802 at start; end figure below.

## Cannibalisation verdict
crystal-vape (377) and crystal-disposable-vapes (187) own "crystal vape" and the Crystal Prime / Pro Max / Galaxy terms: neither appears in any H2, H3 or meta here, and crystal-vape is linked once in the intro for people who mean the generic bars. ske-pods owns "ske pods / ske vape pods" (pods H2 uses "SKE Crystal Refill Pods" and links ske-pods); ske-crystal-nic-salts owns "ske crystal nic salts" (product H3 only, collection linked). This page owns ske vape, ske vapes, ske crystal, ske bar. **Differentiated.**

## Products featured (ShopifyQL net_items_sold, 120 days, product_title CONTAINS SKE)
SKE Crystal Nic Salts 10ml 1,210; SKE 600 Pro pods 821; CL6000 pods 554; Bar 15000 refill pods 435; CL6000 kit 330; Crystal Pro 600 kit 316; SKE Bar 600 kit 91 single plus 176 boxes of 10 and 35 reviews at 4.89 (most reviewed). Tables: 12 kits, 10 pods, 8 liquids, all ACTIVE and in stock; see `products.json`. Flavour best sellers from a variant-level ShopifyQL query (Strawberry Burst, Lemon and Lime, Cola Ice, Blue Razz Lemonade, Tobacco).

## Specs provenance
VOS metafields: all battery sizes (400 / 800 / 850 / 950 / 1250mAh), pod volumes, 1.1 ohm coil on 600 Pro, pod-to-kit compatibility (600 Pro pods to 600 Pro kit, Crystal Plus pods to Plus and Plus Max, Bar 15000 sets to Bar 15K and Bar 6K, 30K pods 1.8ml + 8.2ml x2 from the product description). Retailer only (ecigone, vaping360, versedvaper snippets): SKE Bar 600 500mAh and "about an hour" charge, "600 Pro also takes Crystal Plus pods" (stated as unconfirmed on the page). Conflict: 30K Pro Max pods metafield says 2 x 2ml + 2 x 10ml, description says 20ml; page says "about 20ml". Trustpilot omitted.

## Length judgement
3,586 visible words against the 1,500 to 2,000 target: seven blocks, 30 table rows, guide and nine FAQs cannot fit 2,000. Prose trimmed twice; format kept, as on the Vaporesso run.

## Data problems for Raj
1. **VooPoo Musket Vape Mod Kit is in the collection** (title contains "sket"): excluded from the tables; tighten the rule or tag it.
2. **Ske Strip 600** (`ske-strip-600`, active, 6,944 stock) lists a 3.0ml capacity: looks like a legacy single-use listing.
3. **Blue Fusion SKE Bar 600** (`blue-fusion-ske-bar-600-compliant-prefilled-pod-kit`) has no featured image; its Pack of 5 / 10 compare-at is £6.99, below the £15.99 / £30.99 price.
4. **SKE BAR Prefilled Replacement Pods** carry one 1-star review (shown as 1.0 in the table). **SKE Crystal Plus Refillable Empty Pods** (17 units sold) is not in the collection.
5. 10 drafts match the rule (Sikary S6000, SKEY Self Made 5000, six "SKE Crystal Salt 10ml | Wholesale" drafts, two Crystal 600 disposables). Tiger Blood Crystal Pro 600 is out of stock.
6. Product titles carry offers ("Buy 1 Get 1 Free Vape", "3 For £12 Only") that the page quotes only where the price supports it.

## Pushed and read back
Backup metafield, then collectionUpdate (descriptionHtml + seo + title together, pushed twice: the second push added the button titles): no userErrors, read-back matches (Shopify adds a newline after each `<li>`; description.html normalised to match). Meta title 56 chars, description 154. `custom.description_above_collection` (rich text, 3 paragraphs, 111 words, saved as above_collection.json), `custom.subcollections` (6 published collections, subcollections.json) and `vos_seo.description_log` (word_count 3,586, recheck 23 Nov 2026) set and read back. 32 product links and 4 collection links verified live. No em dashes, no compliance line, no ban framing, no outbound links.
