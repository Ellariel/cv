# Danila Valko — CV

Source for my academic CV, published via GitHub Pages:

**→ https://ellariel.github.io/cv/**

## Editing

All content lives in one file, [`index.md`](index.md) — plain Markdown with a short YAML header at the top. Edit it directly and push; GitHub Pages rebuilds automatically, no local build step required.

## Design

- Layout: [`_layouts/cv.html`](_layouts/cv.html)
- Styles: [`assets/css/style.css`](assets/css/style.css) — light/dark follows the visitor's OS setting automatically (no toggle needed), plus a print stylesheet for a clean PDF via the browser's print dialog.
- Icons: [`assets/icons/`](assets/icons/) — small monochrome SVGs that recolor automatically for light/dark via CSS (`mask-image` + `currentColor`), all drawn in the same stroke weight so they read as one consistent set.

To preview locally: install Ruby + Bundler, then

```
bundle exec jekyll serve
```
