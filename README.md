# page-things

A tiny static personal site / collection of pages. This folder contains a handful of simple HTML pages and a small stylesheet meant for local preview or deployment to a static hosting service (GitHub Pages, Netlify, S3, etc.).

Contents

- `index.html` — Home page
- `about.html` — About page
- `blog.html` — Blog listing or single-post page
- `resume.html` — Resume/CV page
- `style.css` — Styles used by the HTML pages

Quick preview (Windows / PowerShell)

1. Open PowerShell and change into this folder:

   ```powershell
   cd P:\GitHub\page-things
   ```

2. Start a simple file server using Python (requires Python 3):

   ```powershell
   python -m http.server 8000
   ```

3. Open a browser and navigate to http://localhost:8000

Notes

- No build step required — these are plain HTML/CSS files.
- To publish:
  - GitHub Pages: push this folder to a branch named `gh-pages` (or use repository settings) and enable Pages.
  - Netlify / Vercel: drag-and-drop the folder or connect your repo and point to this directory.
  - S3: upload files to an S3 bucket configured for static hosting.

Optional improvements

- Add a `LICENSE` file
- Add meta tags and a `favicon` for better SEO and appearance
- Add a small `index.html` redirect or 404 page
- Add a minimal build step (for example, a `package.json` with `serve` or a simple script)

Contact

If you want edits or a different layout, tell me what you'd like changed and I can update the files or add a simple build/deploy script.
