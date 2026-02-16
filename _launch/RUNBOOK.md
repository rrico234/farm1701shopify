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
