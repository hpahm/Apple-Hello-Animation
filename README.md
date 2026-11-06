# Apple Hello Animation

SVG text draw-on animation. Text outline draws first, then fills white. Loops infinitely.

## Files

- `index.html` — single file, no build step. Open in browser.

## What it includes

### Font
- `Macintosh Skeletal Filled` loaded from CDN via `@font-face`
- Animation starts only after `document.fonts.ready` to avoid wrong glyph shape

### Text Animation
- Element: SVG `<text>` with class `.apple-text`
- Class `.draw` added via JS triggers animation

## Customize

- Change text: edit content inside `<text class="apple-text">`
- Change speed: edit `6s` in `animation: appleDraw 6s ...`
- Change color: edit `stroke` and `fill` in `@keyframes`
- Run once: replace `infinite alternate` with `forwards`
- Change size: edit `font-size` in `.apple-text`
