# Apple Vape (`apple-vape`) - report, 26 Oct 2026

**Target:** gid://shopify/Collection/455419461881, live, rule TITLE CONTAINS "Apple" (174 lines). Collection image present.
**Backup:** description was empty, "nothing to back up"; old title + seo snapshotted to `vos_backup.previous` (read back OK).
**Title:** "Apple Vape Flavours | Apple E-Liquids & Disposables" changed to "Apple Vape UK | Apple Ice & Double Apple Kits, Pods & E-Liquids" (63 chars).

## Ahrefs truth (gb)
- **Primary:** "apple vape" 500/mo, KD 0, TP 200 (GSC 158 impr, pos 26.3 on this URL). Slots: H1, intro bold, meta title, FAQ H2, closing.
- **Secondaries:** apple e liquid 300, apple vape juice 250, apple eliquid 200 (liquids H2, guide box, meta description); double apple vape 300 (H3, FAQ; no sibling owns it); double apple lost mary 300 (FAQ); apple flavour vape 200 (FAQ); green apple vape 150 (FAQ); red apple ice vape 150 (H3; GSC pos 4.3 on the Hayati Pro Max Plus 6000 product page); apple ice vape 60 (H1, H3); apple peach elf bar 40 (FAQ); apple pods vape 30 (pods H2).
- **Questions used as FAQs:** matching-terms double apple / sour apple taste; PAA best apple flavour, apple vape cost; GSC "apple rechargeable vape pod", "apple hayati".
- **SERP:** evapo Lost Mary BM6000 product #1, vapeclub pods #3, vapesuperstore e-liquid #7; AI Overview; thin pages.
- **Units:** 860 + 1,240 + 50 + 432 = **2,582** (cap 3,500). Workspace 123,438 to 136,220; the rest is parallel sessions.

## Cannibalisation verdict
sour-apple-flavour-vape owns "sour apple vape" (GSC pos 25), apple-peach-pear-flavour-vape owns "apple peach pear vape" (GSC pos 7.5); both published, kept out of H2s and meta, one linked mention each. **Differentiated**: this page owns apple vape, apple ice vape, apple vape juice and double apple vape.

## Products featured (ShopifyQL net_items_sold, 120 days; 70 apple units across 22 in-stock lines)
1 Red Apple Ice Hayati Rubik 7000 kit (16); 2 Sour Apple / Juicy Peach Hayati Pro Ultra Plus 25000 pods (11) + kit (1), one merged block; 3 Red Apple Ice Bar Juice 5000 10ml (5); 4 Double Apple Lost Mary BM6000 kit (4); 5 Double Apple Elux Legend 10ml (4); 6 Apple Kingston Gazillions 100ml (cheapest per ml at 6p, the shortfill slot). Budget guide box: Apple Edition Lost Mary 4 in 1. Tables: all 22 lines (8 kits, 3 pods, 11 liquids), see products.json.

## Data problems
1. **Rule catches pineapple.** TITLE CONTAINS "Apple" pulls every "Pineapple" product in: about 48 of the ~88 active lines are pineapple, and they outsold true apple. All excluded from the page. Raj should move the rule to a tag or add NOT CONTAINS "Pineapple".
2. **Compare-at below price:** Hayati Rubik 7000 pack of 10 (£77.95 vs £74.99 compare); its 10-pack is no cheaper per kit than the 5-pack (£7.80 both). Most multipacks carry the single-unit compare-at.
3. Hayati Pro Ultra Plus 25000 pods spec says "2 x 1ml prefilled"; kit says 2ml (page uses 2ml).
4. Double Apple Lost Mary BM600 vendor field is "Elf Bar".
5. Apple Blackcurrant Ice Kingston Fantango 100ml spec says 50/50 and MTL while the other Kingston 100ml shortfills say 70/30 sub-ohm; VG ratio left off the table.
6. No sour apple or apple ice page carries a tasting note; the page says so. All notes and specs from VOS pages only.
7. One review across 22 lines. Trustpilot omitted.
8. Length: 2,864 visible words (2,574 without tables). The mandated format cannot fit 1,000 to 1,400; Raj to decide whether to drop blocks.

## Pushed and confirmed
collectionUpdate (descriptionHtml + seo + title): no userErrors; live HTML read back byte-identical to description.html. Meta title 58, description 153. `custom.description_above_collection` (120 words) and `custom.subcollections` (7 published collections) set and read back. `vos_seo.description_log` set (recheck 2026-11-23). 46 links all titled, 6 images with alt, no em dashes, no compliance line, no ban box, brand-before-model check passed.
