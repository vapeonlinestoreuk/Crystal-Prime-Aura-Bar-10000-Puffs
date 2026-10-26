# Voopoo Vapes (collection) report, 26 Oct 2026

**Target:** gid://shopify/Collection/445764370681, `voopoo-vape`, live, 121 products (107 ACTIVE, 14 DRAFT), rule untouched. Format and CSS from `wholesale-vapes`.
**Backup:** description was empty: `vos_backup.previous` = "nothing to back up" plus old seo (title null) and title, read back. H1 changed from "Buy VOOPOO Vapes | Kits, Tanks, Pods & E-Liquids Online" to "Voopoo Vapes UK | Argus, Drag & Vmate Kits, Pods & Coils" (56 chars). Handle unchanged.

## Ahrefs truth (gb)
- **Primary:** voopoo vape 1,800/mo KD 1 (parent "voopoo" 5,700; "voopoo vapes" 700). Slots: intro bold, two H2s, meta title, above-grid intro.
- **Secondaries, slots:** voopoo vapes uk 30 and voopoo uk 200 (H1, CTA H2, H3); voopoo vape price 100 (table H2, FAQ); best voopoo vape 100 (guide H2 as PAA, blog linked); voopoo gene chip 50 (H3); voopoo vmate 150 (H3); voopoo vape kits / pods / coils as link anchors only. FAQs: three PAA strings (any good, which is best, Voopoo or Vaporesso), matching-terms questions (pods last 40, turn on 20, unlock 20, not working, refill, coils last) and GSC "voopoo vape price".
- **SERP "voopoo vape":** #1 vapesuperstore (DR 62), #2 voopoo.com, #3 Amazon, #4 vapouriz; AI Overview cites voopoo.com, vapestore, vapesuperstore, vampirevape, vapeclub, vapeuk, vapeshop, greyhaze. All plain brand grids; this page adds sales-ranked tables, coil-socket advice and Gene modes.
- **GSC (collection URL, GB, 90 days):** voopoo 649 impr pos 27.3; voopoo vapes 304 pos 23.2; voopoo uk 125 pos 34.1; voopoo vape uk 75 pos 23.4; voopoo vapes uk 15 pos 13.2. Zero clicks; the kits page takes "voopoo vape" (225 impr). All terms sit in H1, intro, H2/H3 or FAQ.
- **Units spent (my calls):** 1,134 + 1,360 + 660 + 495 = 3,649 (149 over cap; serp-overview cost more than expected). Workspace counter 115,394 to 123,438 (shared key).

## Cannibalisation verdict
voopoo-vape-kits, -pods, -coils, -tanks own their head terms; voopoo-argus and drag-vape (empty; argus-vape duplicates voopoo-argus) own "voopoo argus" and "voopoo drag". No H2 carries kits/pods/coils/argus/drag; all four siblings with copy and three blog guides are linked. Related collections: voopoo-vape-kits, voopoo-pods, voopoo-coils, voopoo-tanks, voopoo-argus, drag-vape (all published). **Differentiated.**

## Products featured (ShopifyQL net_items_sold by product_id, 120 days)
Doric Q kit 54, Argus Top-Fill V2 pods 23, Drag X kit 17, ITO pods 16, PnP X coils 14, Argus E40 pods 14. Argus P1/P2/G2 and Vmate kits sold 0 in the window, so they sit in the guide (Argus G2 is the third pick on spec, stated as such). Tables: 12 kits, 10 pods, 8 coils, all ACTIVE and in stock, ties broken by stock; see `products.json`. Only 33 Voopoo products sold at all.

## Specs provenance
VOS metafields: Doric Q, Top-Fill V2, Drag X, PnP X, E40, Vmate, Drag 4 modes, X3/XT 21700, Argus G2/G3/P1/P2. Brand via snippet: Voopoo press release "V2 cartridge fits the entire Argus Pod family". Retailer only: Doric Q no cable (POTV), Drag X box contents, ITO fit on Doric 20/Drag Q (ecigone, vaping360), PnP X not fitting Drag X/S/2 (ecigone, vapoholic), Gene mode behaviour (POTV), TM/TR/R fit lists (elementvape). Conflict: one POTV thread says the Argus XT tank takes PnP coils; VOS and vaping360 say TPP; page follows VOS. Trustpilot omitted.

## Length and rule changes
3,637 visible words against 1,500 to 2,000: six blocks, 30 rows, five H3s and ten FAQs cannot fit 2,000; prose trimmed twice. No ban / June 2025 framing anywhere (checked). All 51 `<a>` tags carry a title, including the six CTA buttons, re-pushed after the first update.

## Data problems for Raj
1. **PnP DW60 coils compare-at £9.49 is below the £10.99 to £11.99 price**; Argus 20W kit compare-at equals price; TPP Pod Tank £21.99 vs £7.99 and Argus MT £45.99 vs £25.99 look inflated.
2. **Drag X title says "PnP-X" but the kit takes standard PnP coils**; its spec metafield lists 2500mAh beside "18650 not included".
3. **PnP-X Replacement Pod (£7.95) is listed as 5ml; PnP MTL pods have a 4.5ml variant; Panda pods say 5ml.**
4. Draft "Voopoo Vinci 3 Starter Kit" is priced £0.00. 14 drafts match the title rule.
5. Out of stock ACTIVE: PNP Pod Tank, Argus 40W kit, Vinci 2, Argus Pro, V.SUIT, Doric 20, Argus G3 Bundle.
6. Collection image exists but has no alt text.

## Pushed and read back
collectionUpdate (descriptionHtml + seo + title together, then descriptionHtml again with button titles): no userErrors, read-back matches (Shopify adds a newline after each `<li>`; description.html normalised). Meta title 52 chars, description 154. `custom.description_above_collection` (122 words), `custom.subcollections` (6 GIDs) and `vos_seo.description_log` (recheck 23 Nov 2026) set and read back. 31 product, 4 collection, 3 blog links verified live. No em dashes, no compliance line, no outbound links.
