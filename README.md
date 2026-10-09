# Rishit Dwivedi — Portfolio

Static personal portfolio (plain HTML/CSS/JS, no build step).

- `index.html` — main page
- `projects/labflow/`, `projects/cybot/`, `projects/riscv/` — project detail pages (directory `index.html`, pretty URLs)
- `projects/*.html` — redirect stubs from the old URLs
- `assets/` — images (relative paths)

## GitHub Pages
Settings → Pages → Source: "Deploy from a branch" → Branch `main`, folder `/ (root)`.
`.nojekyll` is included so files are served as-is.
- `assets/brand/` — logo + favicons (`/favicon.ico` copy at root)
