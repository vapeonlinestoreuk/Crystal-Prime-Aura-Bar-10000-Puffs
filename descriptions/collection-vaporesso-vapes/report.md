# Vaporesso Vapes (collection) report, 24 Oct 2026

**Target:** gid://shopify/Collection/446187929849, `vaporesso-vapes`, live, 237 products (145 ACTIVE, 91 DRAFT, 1 ARCHIVED), rule untouched. Format and CSS copied from `wholesale-vapes`.
**Backup:** description was empty: `vos_backup.previous` = "nothing to back up" plus old seo and title (read back). H1 changed from "Vaporesso Vapes" to "Vaporesso Vapes UK | Kits, Pods, Coils & Mods". Handle unchanged.

## Ahrefs truth (gb)
- **Primary:** vaporesso vape 2,100/mo KD 0 (parent "vaporesso vapes" 1,200). Slots: intro bold, FAQ H2, CTA H2, meta title.
- **Secondaries, slots:** vaporesso uk 1,000 KD 37 (H1, H3, meta); vaporesso vapes uk 40 (CTA H2); how much is a vaporesso 200 (guide H2, FAQ); vaporesso xros pods 700 (H3); vaporesso gti coils 250, gti coils 150, vaporesso gt coils 70 (H3); vaporesso pod kit 150 (table H2); corex 2.0 pods (H3). FAQs: three PAA strings (best pod, puffs per pod, vape juice) plus matching-terms questions (pods price 90, refill 300, burnt 150, not working 300). Left alone: vaporesso 41,000, best vaporesso vape 450 (blog owns it).
- **SERP "vaporesso vape":** #1 edgevaping (DR 27); AI Overview cites vaporesso.com, vapestore, vapeuk, vapesuperstore, vapeclub, greyhaze; then vapehq, flavourvapour, liberty-flights. All thin brand lists; this page adds sales-ranked tables, per-unit maths and compatibility advice.
- **GSC (collection URL, GB, 90 days):** vaporesso 458 impr pos 11.4; vaporesso vape 204 pos 18.4; vaperesso 84 pos 10.3; vaporesso pod 16 pos 21.6. Zero clicks. Both real terms sit in H1, intro and FAQ.
- **Units spent (my calls):** 880 + 493 + 1,240 = 2,613. Workspace counter moved 94,675 to 106,330 because sibling runs share the key.

## Cannibalisation verdict
vaporesso-kits, -pods and -coils own their head terms, the blog owns "best vaporesso vape". This page owns vaporesso vape / vaporesso vapes uk / vaporesso uk. No H2 carries a sibling term; all five siblings and the blog are linked. **Differentiated.**

## Products featured (ShopifyQL net_items_sold, 120 days)
Dojo Blast 10k Pods 861, XROS COREX 2.0 Pods 537, Dojo Blast 30K Pro kit 381, Luxe X Pods 103, XROS 3 Mini kit 78, GTi coils 24 (top coil). Skipped: COREX 3.0 pods 178 (H3 and table row), Dojo Liq 154 (liquid, prose line), Dojo 6000 pods 87 (duplicate). Tables: 12 kits, 12 pods, 6 coils, all ACTIVE and in stock; see `products.json`.

## Specs provenance
VOS metafields: XROS pod wattages and kit list, 30K Pro battery/modes/box, XROS 3 Mini specs, Luxe X wattages, GTi resistances. Retailer only (ecigone, elementvape, vaping360 snippets): GTi wattage bands, GT Core NRG/Cascade fit, COREX 3.0 Hive Mesh, Luxe X fit on X2/X3/XR, "30,000 puffs in ECO mode". Trustpilot omitted.

## Length judgement
3,189 visible words against 1,500 to 2,000: the mandatory format (6 blocks, 30 rows, guide, 8 FAQs) cannot fit 2,000. Prose trimmed twice, format kept.

## Data problems for Raj
1. **XROS COREX 2.0 pods compare-at £6.99 is below the £8.99 four-pack price.**
2. **Luxe X Pods compare-at £11.99 vs £5.99**, XROS 3 Mini £19.99 vs £9.99: look inflated.
3. **Dojo Blast 10K kit page says 650mAh and a 10ml container; pods page says 8ml; Vaping360 says 1000mAh.** Page uses the pods figures only.
4. **91 drafts match the title rule**, including a duplicate "XROS Corex 2.0 Mesh Pods" draft with 3,836 stock.
5. **Out of stock ACTIVE:** iTank 2, Armour Max mod, Target 100, Sky Solo Plus, seven XROS bundles.
6. Orca Solo Plus coils has no pack size. 30K Pro title's "Surprise Dojo 10k Kit Free" unverifiable, not repeated.

## Pushed and read back
collectionUpdate (descriptionHtml + seo + title together): no userErrors, read-back matches (Shopify adds a newline after each `<li>`; description.html updated). Meta title 50 chars, description 152. `vos_seo.description_log` set and read back, recheck 21 Nov 2026. 32 product, 5 collection and 1 blog link verified live. No em dashes, no compliance line, no outbound links.


## Restructure 26 Oct 2026 (kit + own pods share one block)
Product blocks rebuilt on the live page, everything else kept: 1 Vaporesso Dojo Blast 10K Kit and Prefilled Pods (kit £8.99, 46 sold, 5.0 from 2; pods £5.99, 861 sold; kit page names the Dojo Blast prefilled pods as its refill); 2 Vaporesso XROS 3 Mini Kit and COREX 2.0 Pods (kit £9.99, 78 sold; pods from £4.49, 537 sold; pod page lists 0.6Ω to 1.2Ω for every XROS kit); 3 Vaporesso Dojo Blast 30K Pro Pod Kit unchanged (it has no separate pod listing, it takes the 10k pods in block 1); 4 Vaporesso Luxe X Kit and Replacement Pods (Luxe X Pod Kit £23.99 is the best-selling ACTIVE Luxe X family kit the pods fit, 7 colours, 5,383 units; pods £5.99 to £6.99, 103 sold); 5 Vaporesso XROS 5 Mini Pod Vape Kit £15.99, 35 sold, fills the slot freed by merging the old blocks 2 and 5; 6 Vaporesso iTank (£9.95, 25 sold, ACTIVE, 2,573 units) and Vaporesso GTi coils (£9.95, 24 packs). Merged-block format: one h3, one price tag with both prices, one badge, Who's it for, a What's in the box line per product, one spec list, one tip box with both value maths, two CTA buttons titled with each product's real name plus " UK". Live data pulled 26 Oct: Dojo 10k pods now 34 flavours at 20mg plus 10 at 10mg (guide box updated from 29); kit listing 25 at 20mg, 10 at 10mg, 650mAh and 36 x 25.1 x 103.3mm from the kit's spec sheet. XROS 5 Mini box line uses only the listing's spec (0.6Ω COREX pod); web sources disagree on pod count and screen, so no screen claim. iTank box line uses only the listing (2ml UK version, Rainbow or Aurora Green). Brand-before-model pass applied across the page (Vaporesso GTX, Vaporesso NRG, Vaporesso XROS Pro 2, Vaporesso Luxe XR Max, Vaporesso Eco Nano, Vaporesso Gen, Vaporesso Target, Vaporesso COREX 2.0/3.0); "Orca Solo Plus Replacement Coils By Vaporesso" is left as the product's real title in the coil table. Checks before push: 59 links, 0 untitled, 0 "view" titles, 0 em dashes, no stock or draft wording. products.json gains featured / featured_block flags and live prices. Pushed descriptionHtml only via collectionUpdate; seo, title, metafields untouched.
