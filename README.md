# Yungee — AfroDownload UI

This repository contains a single-page static UI for "AfroDownload" — a lightweight web interface for discovering, uploading, streaming and downloading Afro music.

Files
- `afropoo` — the deployed HTML file containing the full UI (HTML/CSS/JS). It is currently saved without a `.html` extension at the repository root.

Quickstart (local)
1. Clone this repository:
   git clone https://github.com/sackeye31-cloud/yungee.git
2. Open the UI locally by either:
   - Renaming `afropoo` to `index.html` then opening it in a browser, or
   - Serving the repo root with a static server and visiting the file directly:
     - python3 -m http.server 8000
     - open http://localhost:8000/afropoo

Make it a web root / GitHub Pages
- To serve the UI as the site entry (root), rename `afropoo` to `index.html` in the repo root.
- Alternatively you can move it to `docs/index.html` and enable GitHub Pages to serve from the `docs/` folder in the repository settings.

Notes
- The UI is fully client-side and stores uploads/favorites/downloads in the browser's localStorage. Uploaded audio uses object URLs and will not persist across machines.
- If you want, I can rename/move `afropoo` to `index.html` now (repo root) or to `docs/index.html` and enable a GitHub Pages configuration.

Contact
- Maintainer: sackeye31-cloud
