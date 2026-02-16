# Launch Changelog

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
