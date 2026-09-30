# krunalgada.github.io

Personal site of Krunal Gada — Senior Data Engineer (Azure & Microsoft Fabric).

Plain static HTML, no build step.

- `index.html` — home page (edit this to update the profile/CV content)
- `assets/` — images and favicon
- `dist/` — knowledge base and articles (Obsidian export); old template pages here now redirect to `/`
- `.nojekyll` — tells GitHub Pages to serve files as-is
- `vercel.json` — tells Vercel to skip install/build and serve the repo root

## Deploy
- **GitHub Pages:** Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
- **Vercel:** import the repo; `vercel.json` handles the rest.

Preview locally: `python -m http.server` then open http://localhost:8000
