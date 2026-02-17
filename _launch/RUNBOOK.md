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

## 2026-02-17 — Phase 3 & 4 Progress

### Where we left off
- Completed Phase 2: premium polish CSS applied to warm-fuzzy sections.
- Completed Phase 3: added optional video embed to Our Why section and created a new **Warm Fuzzy – How It Works** section (note: this section is ready but not yet visible because `templates/index.json` is huge and cannot be edited via GitHub UI).
- Open PRs: #4 (premium polish), #5 (Our Why video embed), #6 (How It Works section).

### Next actions
1. Add the new `warm_fuzzy_how_it_works` section to the home page. Ideally by updating `templates/index.json`; if not possible via code, coordinate with a store admin to add it via the Shopify Theme Editor.
2. Begin Phase 4 (Merchandising & Guided Path). Improve the "Start Here" path and refine product card microcopy and badges. Create a new branch and PR for these changes.
3. Proceed to Phase 5 (Performance & UX). Enhance lazy loading and reduce layout shifts; adjust tap targets for mobile.
4. Continue updating the runbook, changelog, and evidence files at each milestone.

### Obstacles
- The `templates/index.json` file is extremely large and cannot be edited through GitHub's web interface. As a result, we couldn’t add the How It Works section to the home page programmatically. The workaround is to add the section manually via the Shopify Theme Editor once available.
