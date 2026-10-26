# Blue Razz Lemonade Vape (`blue-razz-lemonade-flavour-vape`) - report, 26 Oct 2026

**Target:** gid://shopify/Collection/433044914425, live, 90 lines (TITLE CONTAINS "Blue Razz" AND inventory > 0). Collection image present.
**Backup:** description was empty, "nothing to back up"; old title + seo snapshotted to `vos_backup.previous` (read back OK).
**Title:** changed to "Blue Razz Lemonade Vape | Kits & 10ml Nic Salts" (47 chars).

## Ahrefs truth (gb)
- **Primary:** "blue razz lemonade vape" 700/mo, KD 0 (GSC 65 impr, pos 41.1). Slots: H1, intro bold, meta title, FAQ H2.
- **Co-head:** "blue razz lemonade" 600/mo (GSC 22 impr, pos 39.9): H1, meta, PAA FAQ.
- **Secondaries:** blue razz lemonade vape juice 250 (liquids H2, FAQ); elf bar blue razz lemonade 200, elf bar 600 70, elfliq 90 (Elf Bar FAQ, block 2); blue razz lemonade hayati 150, hayati pro max blue razz lemonade 100 (GSC pos 7; Hayati FAQ, block 5 badge); e liquid / nic salt / liquid (table intro, H3); blue razz lemonade disposable 20 (GSC pos 13, H3); blue raspberry lemonade vape 30 (PAA FAQ); al fakher crown bar blue razz lemonade (GSC pos 2.3, FAQ). "lost mary" 150 and "crystal" 60 left out: no in-window seller to anchor them.
- **SERP:** top 10 is all single-product pages (Evapo Elfliq #4, Vape Green #5, Vape Club #6); no collection page ranks. Four PAAs used as FAQ questions word for word.
- **Units:** 704 + 960 + 810 + 50 = **2,524** (cap 3,500). Workspace counter 123,438 to 136,220; the rest is parallel sessions.

## Cannibalisation verdict
`blue-razz-ice-vape` (394 lines, has copy) owns "blue razz vape" / "blue razz ice vape": neither is in an H2 or the meta title; one FAQ links to it. Cherry, gummy bear and pink lemonade siblings get one link each. All six related collections verified published. **Differentiated.**

## Products featured (ShopifyQL net_items_sold, 120 days, 14 units)
1 Hayati Pro Max 10ml (5), 2 Elf Bar Elfliq 10ml (4), 3 Bar Juice 5000 10ml (2), 4 Al Fakher Crown Bar 30K Hypermax kit (1), 5 Hayati Pro Max Plus 6000 kit (1). Elf Bar 600 kit (1) sits in the kits table, budget guide box and Elf Bar FAQ rather than a block, to hold length down. Brand units: Hayati 6, Elf Bar 5, Bar Juice 2, Al Fakher 1. Tables: 3 liquids, 3 kits (products.json).

## Rule recommendation
Change the rule to TITLE CONTAINS "Blue Razz Lemonade": "Blue Razz" pulls every gummy bear, cherry, pineapple, blackcurrant and ice line into a page that owns the lemonade term only.

## Data problems
1. **Compare-at below price:** Elf Bar 600 (£3.99 compare on all packs), Elfliq (£5.99 compare on the £10 and £19.99 packs), Bar Juice 5000 (£3.99 compare on multipacks).
2. Elfliq spec says "10mg and 20mg" but 5mg variants are live; spec lists both "Made in the UK" and "Made in China".
3. Al Fakher Crown Bar 30K page states no nicotine strength; omitted. Web results only call it "Al Fakher Hypermax 30K" (Vaping360, retailer only).
4. Bar Juice 5000 Pack of 5 / 15mg variant has 0 inventory.
5. Elfliq VOS title has no brand; page writes "Elf Bar Elfliq" per the brand rule.
6. No reviews on any featured line; dashes printed. Trustpilot omitted.
7. No VOS tasting note for pink lemonade or blue razz ice; the taste H3 quotes the Hayati 6000 and Bar Juice pages only.

## Length note
2,179 visible words against the 1,000 to 1,400 flavour target. One block and one FAQ were already cut; the mandated format cannot fit the target. Raj to decide whether to drop more.

## Pushed and confirmed
collectionUpdate (descriptionHtml + seo + title): no userErrors, read-back identical. Meta title 56, description 154. `custom.description_above_collection` (127 words), `custom.subcollections` (6 GIDs) and `vos_seo.description_log` (recheck 2026-11-23) set and read back. Zero untitled links, no em dashes, no compliance line, no ban box.
