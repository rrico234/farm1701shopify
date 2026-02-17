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

## 2026-02-17/02-18 — Phase 5 progress & QA

- Verified contact page and shipping & pickup policy show correct phone, address, hours, shipping schedules, rates, and pickup details.
- Confirmed shipping policy accessible via `/policies/shipping-policy`; refund/terms/privacy pages currently 404 and will require creation via Shopify admin.
- Verified trust copy in product pages and cart summary; risk reversal still not near ATC.
- Checked staging theme preview for home page – warm-fuzzy sections not fully integrated due to `index.json` editing barrier.
- New microcopy improvements for product cards planned but not implemented due to snippet complexity.

**Next actions:**
1. Continue to refine product card microcopy and badges via snippet modifications (requires careful editing).
2. Work on performance & UX improvements (lazy loading images, adjust CSS for tap targets).
3. Plan final QA checklist (Gates A–I) once all PRs merge and new sections added.
4. Seek manual assistance or alternative method to update `templates/index.json` to include the "How It Works" section and finalize home page.
