# Cola Vape (`cola-ice-flavour-vape`) - report, 26 Oct 2026

**Target:** gid://shopify/Collection/433044750585, live (4 channels), 99 lines (TITLE CONTAINS "Cola" AND inventory > 0). Collection image present.
**Backup:** description was empty, "nothing to back up"; old title + seo snapshotted to `vos_backup.previous` (read back OK).
**Title:** "Cola Ice Flavour Vape" changed to "Cola Vape | Cola Ice Kits, Pods & E-Liquids" (43 chars).

## Ahrefs truth (gb)
- **Primary:** "cola vape" 450/mo, KD 0, TP 250, parent of cola vape juice (500), cola vapes, coca cola vape, cola disposable vape. GSC 13 impr, pos 42. Slots: H1, intro, three H2s, meta title.
- **Co-head:** "cola ice vape" 300/mo (GSC 25 impr, pos 25.4, 1 click; cola ice vapes 13, cola ice disposable vape 9, iced cola vape 6). Slots: H1, meta title, H3, three FAQs.
- **Secondaries:** cola e liquid 500 (H2 + FAQ), cola vape juice 500 (FAQ), cola lime vape 100 (H3), cola lost mary 100 (FAQ), coca cola vape 90 (PAA FAQ), cola disposable vape 20 (H3), cola elf bar 30 / GSC 97 impr (FAQ), cola nic salt 0 (H3). cola ice crystal bar 150 skipped: no in-stock seller.
- **SERP "cola vape":** AI Overview; vapeclub cola pods #2 (DR 70), evapo BM6000 #3, vapekit cola e-liquid #4. PAA used: Is there a Coke flavored vape? / Is cola a good vape flavour? "cola ice vape": theelectroniccigarette Crystal Bar liquid #2, SKE 600 kit pages #4-5; PAA "Is cola ice vape good?". Health PAAs skipped.
- **Units:** 836 + 880 + 374 + 256 + 0 (GSC) = **2,346** (cap 3,500). Workspace 124,142 to 136,220 (parallel sessions). GSC returned 502 twice before succeeding.

## Cannibalisation verdict
cherry-cola-vape-flavour (32 lines, has copy) owns "cherry cola vape": linked once in the intro, kept out of every H2 and the meta. This page owns "cola vape" and "cola ice vape". drink-inspired-e-liquids is live (67 lines) and linked. **Differentiated.**

## Products featured (ShopifyQL net_items_sold, 120 days, 131 cola units)
1 Cola Elf Bar Elfliq 10ml (30), 2 Raspberry Cola Hayati Pro Ultra Plus 25000 pods (22), 3 Cherry Cola Elf Bar Elfa pods (10), 4 Cola Lost Mary BM6000 kit (9), 5 Cola Ice SKE Bar 600 kit (8), 6 Cola Ice Hayati Pro Max Plus 6000 kit (4) + pods (6), merged per the kit-and-pods rule. Cherry Cola Elf Bar Elfliq (11) skipped for a block as a second Elfliq bottle; it is in the table and two FAQs. Tables: every in-stock seller, 8 kits, 4 pods, 8 liquids (products.json).

## Data problems
1. **Mis-tagged by the "Cola" rule:** 11 Dubai chocolate / Kunafa products ("Chocolate" contains "cola") and 3 Pina Colada liquids are in the collection. Excluded from the page; a tag-based rule would fix it.
2. **Handle mismatch:** "Cola Lime Hayati Pro Max 10ml Nic Salt" lives at `cherry-lime-hayati-pro-max-10ml`.
3. **Compare-at below price:** Cherry Cola Elf Bar 600 (£3.99 vs £4.99); Lemon Cola Ice Hayati Rubik 7000 ten-pack (£77.95 vs £74.99). Lost Mary BM6000 and Elfliq multipacks carry the single-unit compare.
4. Hayati Pro Ultra Plus 25000 pod metafield says "2 x 1ml"; kit pages say 2ml. Page gives no ml for the pods.
5. Cola Elfliq metafield lists 10mg and 20mg; variants also sell 5mg. Page follows the variants.
6. Classic Cola Kingston Cola 100ml carries a 1.0 rating from 1 review (printed).
7. Trustpilot figure omitted (not in this run's data).

**Specs:** all from VOS product_specifications metafields and VOS descriptionHtml (tasting notes from the Cola Ice and Cola Lime Hayati Pro Max Plus 6000 pages and the Cherry Cola Elfa page). No retailer-only specs. Competitor prices omitted (unreachable).

## Length note
2,516 visible words (2,240 without tables). The 1,000 to 1,400 flavour target cannot hold six blocks, three tables, three guide boxes, four H3s and eight FAQs; prose was cut hard. Raj to decide whether to drop blocks.

## Pushed and confirmed
collectionUpdate (descriptionHtml + seo + title): no userErrors, read-back identical to description.html. Meta title 57 chars, description 154. `custom.description_above_collection` (118 words), `custom.subcollections` (6 published collections) and `vos_seo.description_log` (recheck 2026-11-23) set and read back. No em dashes, no compliance line, no ban box, no footers; every link titled, every alt brand + product + view.
