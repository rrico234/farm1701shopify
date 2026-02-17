# Launch Changelog
## 2026-02-17 — P5 Warm Fuzzy QA & Merchandising progress
- Verified Contact page displays correct phone, address, business hours, and shipping/pickup details.
- Reviewed Shipping policy page for shipping schedule, transit times, flat-rate shipping rates and free local pickup instructions.
- Noted missing Refund policy (404) and Terms/Privacy pages to be added.
- Verified trust & risk reversal copy on product pages and cart; contact info and promise appear correctly.
- Continued investigating product-card microcopy improvements but deferred due to Liquid editing complexity.
- Documented progress in runbook (Phase 5 progress & QA) and created PR (#10).
- Added new evidence screenshots for home page hero, deposit sections, bottom trust copy, contact page, and shipping policy.
- Remaining tasks: add "How It Works" section to home page (large JSON edit), refine product cards & microcopy, finalize performance improvements and final QA.

### Revert
- Revert this PR commit to fully undo these changelog additions.

## 2026-02-16 — P0 Warm Fuzzy CRO pass
- Home: reordered to hero → our why → value props → start here → testimonials → story teaser → email capture.
- Home hero defaults updated with founder-forward copy and direct CTA paths.
- Added warm fuzzy sections: `warm_fuzzy_our_why`, `warm_fuzzy_value_props`, `warm_fuzzy_testimonials`, `warm_fuzzy_story_teaser`, `warm_fuzzy_email_capture`.
- PDP: added near-ATC trust + guarantee line, “why this cut” bullets, and FAQ accordion content for shipping/pickup/packaging/storage.
- Cart: added trust/contact/pickup/guarantee reassurance block near checkout summary.
- Collections: added top intro reassurance text for beef/chicken/pork handles without changing product grid behavior.
- Added additive `assets/warm-fuzzy.css` and included it in `layout/theme.liquid` for typography, spacing, and long-text readability.
- Removed “Welcome to our store” placeholder from announcement bar.

### Revert
- Revert this PR commit to fully undo.
- Or manually remove warm fuzzy section entries from `templates/index.json` order and delete the added section files.
