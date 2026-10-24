# DTL Vape Kits (collection) - report, 24 Oct 2026

**Target:** gid://shopify/Collection/472818024697, `dtl-vape-kits`, live, manual, 43 products. ruleSet, products, image, handle, sortOrder untouched.
**Backup:** description was empty: `vos_backup.previous` = "nothing to back up" plus old seo and title; read back OK.

## Free 10ml claim and H1
Not verifiable collection-wide: only 10 of 43 product titles carry a free-liquid line, nine of them MTL/RDL pod kits; no box mod or DTL pod mod has it. The MTL page says the offer is per listing. **Claim removed from H1, meta and copy**; one FAQ says it applies only where the listing states it. **H1 changed** to "DTL Vape Kits UK | Sub Ohm Direct to Lung Kits" (46 chars).

## Ahrefs (gb)
- **Primary:** dtl vape 600/mo KD 0 (+ dtl vape kit 60, dtl vape kits 20): H1, intro bold, meta title, FAQ and CTA H2s.
- **Secondary slots:** sub ohm vape kit 700 (H1, meta), sub ohm vape 800 (intro), best sub ohm vape kit 300 (guide H2), sub ohm kit 200 / sub ohm mod 90 (table 1 H2), dtl pod vape 40 (table 2 H2), dtl vape coils 30, sub ohm e liquid 200, mtl vs dtl 150 (H3s), direct to lung vape 300 (CTA H2).
- **SERP "dtl vape":** AI Overview (vapesuperstore explainer, misteliquid collection); #2 vpz dtl-kits DR 38, #3 vapeuk sub-ohm DR 63, #5 misteliquid, #6 ecigone blog. **"sub ohm vape kit":** vapeuk, vapestore, vampirevape, misteliquid blog, vapeclub, ecigone.
- **PAA:** seven PAA strings from both SERPs are the first seven FAQ questions verbatim; the lung-recovery one was skipped.
- **GSC:** gsc-keywords returned 502 four times over 20 minutes; no rows.
- **Units:** 2,282 metered (overview 680, matching terms 896, SERPs 706). Workspace counter 94,675 to 106,330; shared with other sessions.

## Cannibalisation
rdl-vape-kits (rdl vape kits), best-mtl-vape-kit-for-beginners (mtl vape kit), dtl-vape-tanks (sub ohm tanks), vape-mods, kits: none of their heads in this page's H2s or meta, all five cross-linked. **Differentiated.**

## Products featured (ShopifyQL units, 120 days)
Only two real DTL kits sold: Armour Max 10, Aegis Legend 5 5; everything else 0. Blocks: Armour Max, Aegis Legend 5, Argus GT II (biggest discount, £26), SMOK Mag V8 (no settings), Aspire Veynom EX (cheapest DTL kit £19.99). Tables: Product | Price | Max power | Rating, sorted units then price.

## Data problems
1. **13 of 43 products are MTL/RDL pod kits mis-tagged** (XROS Pro, XROS 4, Xlim Pro 2, Xlim Go, Xlim Classic, Caliburn G3 Pro, EZ.Watt, Ayce Pro, Argus G2, Argus P2, Luxe X Pro, RPM40, Gozee) and they are the collection's real sellers (26, 20, 18 units). Tabled separately; Raj should move them.
2. Compare-at prices to check: Argus GT II £49.99 vs £23.99, Armour Max £72.99 vs £47.99.
3. Low ratings stated on page: Armour Max 3.0 (2), Scar 18 1.0 (1), Xlim Classic 1.0 (1). 36 of 43 products have no reviews metafield.
4. Review-only specs: Aegis Legend 5 IP68, Armour Max 157mm (planetofthevapes, vaping360 snippets). Aegis Legend 5 coil pair conflicts between sources ("varies by edition" on page). Argus GT II tank UFORCE-L per VOS metafield, MAAT at some retailers. Mag V8 tank TFV-Mini V2 per VOS. Everything else from VOS product_specifications.
5. Trustpilot line omitted (unverified).
6. Length 2,884 visible words (394 in three 43-row tables) against the 2,000 target; five blocks, three tables and ten FAQs set the floor. Meta title 54, description 155.

## Pushed and confirmed
collectionUpdate (title + descriptionHtml + seo): no userErrors; read-back matches description.html bar Shopify's newline after `<li>` and `<div class="vos-tip-box">`. `vos_seo.description_log` set, recheck 2026-11-21, returned. 53 VOS links, all handles ACTIVE this run; no outbound links, em dashes or compliance line.
