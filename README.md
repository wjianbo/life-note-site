# Life Note Site

This repository contains a simple static website for the **Life Note** iOS app.

It is intended to provide App Store Connect URLs for:

- Marketing page (`/`)
- Support page (`/support/`)
- Privacy Policy page (`/privacy/`)

## Preview locally

Because this is plain HTML/CSS, you can open `index.html` directly in your browser.

For cleaner local path behavior, run a small static server from the repo root:

```bash
python3 -m http.server 8000
```

Then visit:

- `http://localhost:8000/`
- `http://localhost:8000/support/`
- `http://localhost:8000/privacy/`

## Deploy with GitHub Pages

This site is designed for GitHub Pages with:

- **Branch:** `main`
- **Folder:** `/ (root)`

After pushing to `main`, enable GitHub Pages in repository settings and select the root directory.
