# Simplicrete brand kit

Vector recreation of the existing Simplicrete logo (`Original.png`, supplied by
Anton 2026-09-10) plus social / favicon variants.

## Design

- **Wordmark:** SIMPLICRETE in a high-contrast Didone serif — **Playfair Display**
  (Medium / 500), letter-spaced. Closest free match to the original's typeface;
  swap for the exact font if we ever get the source file.
- **Tagline:** SEAMLESS SURFACE SPECIALISTS, Playfair Display Regular, tracked.
  Chosen by Anton 2026-09-10, replacing the original's "handmade natural beauty"
  (cosmetics wording that didn't fit the trade). Options shown: "Seamless Concrete
  Finishes", "Handcrafted Concrete Finishes", "Decorative Concrete Specialists",
  "Seamless Surface Specialists" (picked — covers microcement, stone carpet, epoxy,
  resurfacing, not just concrete).
- **Frame:** two thin rectangles offset ~28px — the layered double-border from the
  original.
- **Colour:** antique gold `#7B5B25` (sampled from the original). Reversed art uses
  off-white `#FBF7EF`.
- Cream background used on tinted variants: `#F6F1E8`.

## Files

Masters (SVG, font pulled from Google Fonts via `@import`):
- `simplicrete-primary.svg` — horizontal lockup, gold on transparent
- `simplicrete-primary-reversed.svg` — off-white on transparent (for gold / dark bg)
- `simplicrete-monogram.svg` — "S" in the double frame, gold on transparent
- `simplicrete-monogram-reversed.svg` — off-white on transparent

PNG exports (rendered 2–4×, ready to upload):
- `simplicrete-primary-white.png` / `-cream.png` / `-reversed.png` (3200×1280)
- `simplicrete-social-square-white.png` / `-cream.png` / `-gold.png` (2160×2160)
- `simplicrete-avatar-gold.png` / `-cream.png` (1536×1536) — profile pictures
- `simplicrete-favicon-64.png` (256×256) — site favicon / small icon
- `simplicrete-banner-1500x500.png` (3000×1000) — Facebook / X cover

`../logo.svg` and `../logo-icon.svg` in the site repo are copies of the primary
and monogram masters.

## Rebuild

`node C:/Users/info/tmp-brand/build.js` — regenerates every PNG from the inline
SVG definitions in that script. Needs headless Chrome + internet (for the font).

## Status

Tagline decided (SEAMLESS SURFACE SPECIALISTS). Still pending: Anton's sign-off on
the recreation, then wire `../logo.svg` into the site header + set the favicon, and
commit `simplicrete-web`.
