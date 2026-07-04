# Site Refactor Notes

Goal: keep the current site visually unchanged while making the codebase easier to scale.

Current state:

- `index.html` is the live one-page site.
- Styles and browser interactions are currently inline.
- The first refactor branch is `scale-site-foundation`.

Planned structure:

```text
index.html
assets/
  css/
    styles.css
  js/
    app.js
  images/
    README.md
docs/
  site-refactor-notes.md
```

Safe next step:

1. Move the inline CSS from `index.html` into `assets/css/styles.css`.
2. Move the inline browser behavior from `index.html` into `assets/js/app.js`.
3. Add stylesheet and script references back into `index.html`.
4. Confirm the rendered page matches the current site before merging.

No visual redesign should happen in this refactor.
