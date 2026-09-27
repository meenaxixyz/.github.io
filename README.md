# Meenaxi — holding page (plain HTML/CSS)

A single static page. 

## Files
- `index.html` — the page
- `style.css` — all styling
- `logo.svg` — the fish logo (ivory + gold)
- `favicon.svg`, `apple-touch-icon.png` — browser/app icons
- `og-image.png` — image shown when the link is shared
- `CNAME` — your custom domain (meenaxi.xyz)
- `.nojekyll` — tells GitHub Pages to serve the files as-is (no Jekyll)

## Preview locally
Just double-click `index.html`, or drag it into a browser. That's it.
(Optional, for a "real" server feel: `python3 -m http.server` in this folder,
then open http://localhost:8000)

## Publish on GitHub Pages
1. Put these files at the ROOT of your repo.
2. Settings → Pages → Source: "Deploy from a branch" → main / (root).
3. DNS + custom domain as before; the CNAME file already claims meenaxi.xyz.

## Editing
- Wording: edit `index.html` (mission line, the three words, footer).
- Colours/fonts: the variables at the top of `style.css`.
- Logo: replace `logo.svg`.