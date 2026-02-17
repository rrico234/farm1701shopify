# Launch Changelog
## 2026-02-17 — P3 & P4 Warm Fuzzy Progress

- Phase 2: Added `warm-fuzzy-polish.css` for premium spacing, typography, card polish, alternating backgrounds, and improved button hierarchy, and imported it into `theme.liquid`.
- Phase 3: Added optional video embed capability to the **Warm Fuzzy Our Why** section (new `video_url` setting).
- Phase 3: Created **Warm Fuzzy How It Works** section with 3-step blocks and presets (file `sections/warm_fuzzy_how_it_works.liquid`) along with new CSS classes for the section.
- Updated `_launch/RUNBOOK.md` with a new entry summarizing Phase 3 & 4 progress and next actions.
- Opened PRs for premium polish (#4), video embed (#5), how-it-works section (#6), and runbook update (#7). These PRs auto-merge once checks pass.

### Revert
- Revert PRs #4, #5, #6, and #7 to fully undo this entry.
- Delete the added files (`assets/warm-fuzzy-polish.css`, `sections/warm_fuzzy_how_it_works.liquid`) and remove the `video_url` setting from `sections/warm_fuzzy_our_why.liquid` if manually reverting.


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
