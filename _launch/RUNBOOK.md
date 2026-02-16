# Warm Fuzzy P0 Runbook

## Completed in this PR
- No-admin default content path implemented directly in theme files.
- Trust/guarantee and shipping/pickup certainty content placed near decision points (home/PDP/cart/collections).

## Next actions
1. Verify on preview theme that homepage section order matches acceptance exactly on mobile.
2. Spot-check at least one live beef/chicken/pork collection handle for intro text.
3. Validate one product page above-the-fold content on desktop + mobile.
4. Validate cart summary reassurance block is visible near checkout CTA.
5. If copy tweaks are needed, edit section defaults only (no structural changes).

## Rollback
- Revert PR merge in GitHub.
- Optional surgical rollback: remove warm fuzzy sections from `templates/index.json` and delete `sections/warm_fuzzy_*` files plus CSS include.

## Where we left off (2026‑20‑16)

Warm fuzzy P0 sections are live on the staging theme and verified via the post‑sync baseline. We have completed a Phase 1 Warm Fuzzy Audit (see below) to identify friction points and opportunities.

### Next 3 actions

1. **Formatting & Polish PR (Phase 2)** – implement the warm‑fuzzy formatting system (spacing rhythm, typography, polished cards, button hierarchy, alternating section backgrounds) in an additive CSS file loaded after the base theme.
2. **Content Enhancements PR (Phase 3)** – refine founder voice copy, add an “Our Why” media placeholder, and implement a “How it works” 3‑step block; tighten trust block typography.
3. **Merchandising & Guided Path PR (Phase 4)** – improve Start Here links from the home page, refine collection intros, and enhance product card microcopy and badges.

## Phase 1 – Warm Fuzzy Audit Results (2026‑20‑16)

The following pages were audited for warmth and conversion using the six warm‑fuzzy mechanisms. Scores (1–10) reflect the perceived warmth and trust at the time of audit.

| Page | Warm Fuzzy Score (1–10) |
| --- | --- |
| Home | 6 |
| Beef Collection | 5 |
| Chicken Collection | 5 |
| Pork Collection | 5 |
| Product Detail Page (PDP) | 6 |
| Cart | 4 |
| Shipping & Pickup page | 5 |
| Contact page | 4 |
| Recipes hub | 3 |
| Experience hub | 3 |

### Home

- **Friction** – The hero copy is long and the product grid appears early, pushing down our story; there is no dynamic media such as video; spacing is inconsistent across sections.
- **Warmth deficits** – Limited human or farm imagery; testimonials are generic and lack faces; the “Our Why” text is long and doesn’t highlight authenticity; risk‑reversal copy isn’t visible near the top.
- **ROI opportunities** – Refine hero copy and visuals to emphasise real farmers and shorten text; highlight a “Start Here” path to best‑sellers; add a founder portrait; unify section spacing and max text widths.

### Beef/Chicken/Pork Collections

- **Friction** – Collection intros sit below the product grid and are easy to miss; filter and sort controls distract from storytelling; product cards lack context about why each cut is special.
- **Warmth deficits** – No human or farm imagery; trust and guarantee copy only appears in the footer; shipping and pickup clarity isn’t visible.
- **ROI opportunities** – Add a small hero banner or header with reassurance copy; reposition reassurance bullets near the top; highlight shipping/pickup options; feature recommended cuts or curated bundles.

### Product Detail Page

- **Friction** – The risk‑reversal guarantee isn’t near the Add to Cart button; the “Why this cut” bullets are below the fold; FAQ accordion is lengthy; no related products are suggested.
- **Warmth deficits** – Lacks founder voice above the fold; shipping/pickup details aren’t summarised near price; trust icons aren’t visible near the CTA.
- **ROI opportunities** – Add guarantee text adjacent to the Add to Cart button; relocate shipping/pickup bullets near the price; surface cross‑sell suggestions or testimonials; emphasise our guarantee.

### Cart

- **Friction** – The slide‑out cart lacks reassurance or clarity on shipping costs; trust copy and guarantee are absent; cross‑sell suggestions clutter the small space.
- **Warmth deficits** – No human elements; fonts and spacing are inconsistent; CTA emphasises checkout without highlighting pickup options.
- **ROI opportunities** – Add a trust strip below the total summarising shipping, pickup, and guarantee; include the phone number and address; emphasise UPS cold‑packed shipping and local pickup hours.

### Shipping & Pickup page

- **Friction** – The text is dense and lacks clear bulletisation; local pickup and shipping processes aren’t distinguished; deadlines or cutoffs aren’t highlighted.
- **Warmth deficits** – No images or icons to illustrate the process; trust and guarantee aren’t emphasised; team contact details are buried.
- **ROI opportunities** – Restructure into a three‑step process with icons; emphasise hours, address, and contact number; include a small map or call‑out; highlight the cold‑pack guarantee.

### Contact page

- **Friction** – Contact form is minimal with little context; typical response times aren’t communicated; location and hours aren’t emphasised.
- **Warmth deficits** – Absent team photos; the page feels utilitarian; there’s no copy emphasising our friendly customer service.
- **ROI opportunities** – Add team headshots or a farm image; emphasise personal responses and typical response times; prominently display the phone number, hours, and pickup address.

### Recipes & Experience hubs

- **Friction** – Navigation is unclear and categories aren’t curated; large lists overwhelm users; there’s little differentiation between types of content.
- **Warmth deficits** – No storytelling about who created recipes or experiences; images of prepared dishes or farm activities are missing; content feels generic.
- **ROI opportunities** – Introduce a hero or intro section with a description and imagery; curate recipes into sections like “Easy Weeknight Meals” or “Grill Favourites”; add user stories/testimonials; encourage newsletter sign‑ups for more recipes.
