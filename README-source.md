# Dors variation image library

Generated from the 3 Dors PDFs using the user-approved tuned2 crop logic for structured code-under-drawing pages, plus hero-page fallbacks for codes that only appeared on editorial/image pages.

- total canonical codes in seed: 139
- extracted image matches: 139
- missing after full pass: 0

## Match types
- `direct_grid`: code printed under its own door drawing; isolated crop
- `direct_single_column`: code printed in a single-column structured page; isolated crop
- `hero_single_code_page`: editorial/hero page fallback where one canonical code owns the page

## Notes
- Direct pages are treated as high-confidence.
- Hero fallbacks are medium_high confidence and should be QA reviewed if these images are used downstream in a product UI.
- No canonical codes missing in this pass.
