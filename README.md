# aafrin.xyz

Personal site. Static — no build step.

## Files
- `index.html` — the whole site (markup + logic)
- `support.js` — runtime that renders `index.html`
- `images/` — article thumbnails
- `Sameena-Aafrin-Resume.pdf` — linked from the work section

## Run locally
Serve the folder over HTTP (opening the file directly with `file://` will not load the runtime):

```
python3 -m http.server 8000
```

Then open http://localhost:8000

## Deploy on GitHub Pages
Push these files to the repo root (or a `docs/` folder), then in Settings → Pages pick the branch and folder. `.nojekyll` is included so nothing gets filtered.
