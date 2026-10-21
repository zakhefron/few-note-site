# few-note-site

Marketing site and in-browser demo for [FewNote](https://github.com/zakhefron/few-note) — an ultra-lightweight, native macOS notepad.

## Live

https://zakhefron.github.io/few-note-site/

## What's here

- `index.html` — the marketing page: hero, interactive "Try it" dot-matrix, features, shortcuts, install.
- `assets/` — screenshots, demo gif, app icon.

The "Try it" section runs a real dot-matrix renderer in the browser: type directly on the matrix, pick an ink, and adjust the text size.

## Development

Static site, no build step. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

Pushes to `main` publish via GitHub Pages.