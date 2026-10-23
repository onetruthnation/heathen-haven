# Heathen Haven

A lightweight, dependency-free static website prototype for **Heathen Haven — the only free port left**. It gives writing, music, visual work, and community ideas a shared harbor while keeping unfinished material visibly labeled as placeholders.

The project names shown on the homepage are seeds supplied by the owner. No excerpts, tracks, artwork, event details, or community plans have been invented.

## Run locally

No package install or build step is required. From the project folder, run either:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

You can also open `index.html` directly in a browser. A local server is recommended for a more realistic preview.

## Customize

- **Homepage copy and sections:** edit `index.html`.
- **Colors, layout, and responsive rules:** edit the custom properties at the top of `styles.css`, then the styles below them.
- **Mobile navigation:** edit `script.js`.
- **Harbor mark:** replace `assets/harbor-mark.svg` with your own SVG or image and update the icon reference in `index.html` if its filename changes.
- **Project cards:** replace each `PROJECT SEED` or `PLACEHOLDER` entry with approved material when it is ready. Remove the seed label once a real item is published.

The page uses Google Fonts (Manrope, Newsreader, and DM Mono) when a connection is available and falls back to system fonts when it is not. The lighthouse artwork is inline SVG in `index.html`, so there are no image downloads or build dependencies.

## Publish with GitHub Pages

1. Push these files to the repository's `main` branch.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. GitHub Pages will show the published URL and deployment status in the same settings area.

Because this is a plain static site, it needs no framework configuration, secrets, or server process. Changes pushed to the selected branch and folder will trigger a new Pages deployment.

## Files

```text
.
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── harbor-mark.svg
└── README.md
```
