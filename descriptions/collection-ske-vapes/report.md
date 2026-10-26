# SKE Vapes (collection) report, 26 Oct 2026

**Target:** gid://shopify/Collection/443752055033, `ske-vapes`, live, 109 products, rule untouched. CSS from `wholesale-vapes`. Collection image present.
**Backup:** description was empty: `vos_backup.previous` = "nothing to back up" plus old seo and title. **H1** changed from "Buy SKE Crystal Vape | All SKE Vape Flavours In Stock" to "SKE Vapes UK | SKE Crystal Kits, Refill Pods & Nic Salts" (56 chars). Handle unchanged.
**Raj's four mid-run rules applied:** no ban framing anywhere (problem box, one H3 and the "illegal" FAQ deleted); every model name carries its brand, rival Crystal Prime / Pro Max / Galaxy names replaced by "Crystal-branded bars from other makers"; every `<a>` title, buttons included, is the brand-first full product or collection name plus "UK" (no "view" phrasing); every `<img>` alt is brand + product + what the picture shows.

## Ahrefs truth (gb)
- **Primary:** ske vape 1,700/mo KD 3 (twin ske vapes 900); the only striking-distance GSC term. Slots: intro bold, H1, FAQ H2, CTA H2, meta title.
- **Secondaries, slots:** ske crystal 1,300 (H1, table H2s); ske crystal vape 5,800 (parent "crystal vape", intro only); ske bar 1,200 / ske bar 600 500 (H3, guide, FAQ); ske 600 pro pods 1,400 (H3, FAQ); ske bar 15k 900 (H3, guide); ske crystal cl6000 800 (H3, FAQ); ske crystal plus 700, ske crystal 4 in 1 250 (compatibility H3); ske vape flavours 250 (H3); ske 30k pro max 400 (table). FAQs from matching-terms questions and PAA; "Is SKE vape safe" left out.
- **SERP "ske vape":** #1 skebarvape.co.uk, then vapeuk (DR 64), vapeclub, vapesuperstore, uk.skevape.com; AI Overview cites the same plus Totally Wicked. All brand lists, no sales ranking or compatibility guide.
- **GSC (90 days):** ske vape 988 impr pos 14.8; ske crystal 378; ske crystal vape 364; ske crystal vapes 303; ske vapes 129.
- **Units spent (my calls):** 792 + 880 + 525 + 496 = 2,693 of 3,500. Workspace counter 111,802 to 123,438 (shared key).

## Cannibalisation verdict
crystal-vape and crystal-disposable-vapes own "crystal vape" and the Crystal Prime / Pro Max / Galaxy terms: none in any H2, H3 or meta; crystal-vape linked once. ske-pods owns "ske pods" (pods H2 says "SKE Crystal Refill Pods", linked); ske-crystal-nic-salts owns its term (linked). This page owns ske vape, ske vapes, ske crystal, ske bar. **Differentiated.**

## Products featured (ShopifyQL net_items_sold, 120 days)
SKE Crystal Nic Salts 1,210; SKE 600 Pro pods 821; SKE Crystal CL6000 pods 554; SKE Bar 15000 pods 435; SKE Crystal CL6000 kit 330; SKE Crystal Pro 600 kit 316; SKE Bar 600 kit 91 plus 176 boxes of 10, 35 reviews at 4.89 (most reviewed). Tables: 12 kits, 10 pods, 8 liquids, all ACTIVE and in stock (`products.json`). Flavour best sellers from a variant-level query.

## Specs provenance
VOS metafields: batteries, pod volumes, 1.1 ohm coil, compatibility. Retailer only (ecigone, vaping360, versedvaper): SKE Bar 600 500mAh and "about an hour" charge, "SKE 600 Pro takes SKE Crystal Plus pods" (stated as unconfirmed). Conflict: SKE 30K Pro Max pods 24ml in the metafield, 20ml in the description; page says "about 20ml". Trustpilot omitted.

## Data problems for Raj
1. **VooPoo Musket Vape Mod Kit is in the collection** ("sket"); excluded from tables.
2. **Ske Strip 600** (active, 6,944 stock) lists a 3.0ml capacity: looks like a legacy single-use listing.
3. **Blue Fusion SKE Bar 600 kit** has no featured image and a £6.99 compare-at below its pack prices.
4. **SKE BAR Prefilled Replacement Pods** carry one 1-star review. **SKE Crystal Plus Refillable Empty Pods** (17 units) is not in the collection.
5. 10 drafts match the rule (Sikary S6000, SKEY Self Made 5000, six wholesale salts, two Crystal 600 disposables).

## Pushed and read back
3,662 visible words (format plus brand prefixes cannot fit 2,000; prose trimmed twice). Backup metafield, then collectionUpdate (descriptionHtml + seo + title; pushed four times as the rules arrived): no userErrors, read-back matches (Shopify adds a newline after each `<li>`; description.html normalised). Meta title 56 chars, description 154. `custom.description_above_collection` (115 words), `custom.subcollections` (6 published collections) and `vos_seo.description_log` (3,662 words, recheck 23 Nov 2026) set and read back. 32 product and 4 collection links verified live. No em dashes, compliance line, ban framing or outbound links.

## Restructure 26 Oct 2026
Kit-and-pods rule applied: seven blocks became six. 2 SKE 600 Pro kit (316) + pods (821); 3 SKE Crystal CL6000 kit (330) + pods (554); 4 SKE Bar 15K kit (181, £8.99, 5.0 from 5) + refill pods (435); 5 SKE Bar 600 kit unchanged; 6 new SKE 30K Pro Max kit (92, £10.99, 20 flavours, 5.0 from 1) + SKE 30K Pro Max Replacement Pods (119, £7.99, 5.0 from 1). Blocks 1 and 5 unchanged apart from numbering. Each merged block: one price tag with both prices, one badge, Who's it for, What's in the box (kit line + pod line), one spec list, one tip box, two titled buttons; kit image kept with an alt naming kit and pods. Intro count sentence updated to six. Flavour leaders for the SKE 30K Pro Max and SKE Bar 15K kit from a variant-level ShopifyQL query (120 days). SKE 30K Pro Max pack volume stated as "about 20ml" (the product page figure). Checks: 62 links all titled, no "view" titles, no bare model names, no em dashes, 3,996 visible words. Pushed via collectionUpdate (descriptionHtml only) and read back: h3 "2. SKE 600 Pro Kit and Prefilled Pods" live, 6 product blocks. products.json: featured / featured_block flags set.
