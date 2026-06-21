# SIROai website

Static site for GitHub Pages.

## Files
- `index.html` — the site (homepage)
- `assets/` — images referenced by the page
- `.nojekyll` — tells GitHub Pages to serve files as-is (no Jekyll processing)

## Deploy to GitHub Pages
1. Create a new repository on GitHub.
2. Upload the **contents of this folder** to the repo root (so `index.html` sits at the top level, not inside a subfolder).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch **main** and folder **/ (root)**, then **Save**.
6. Wait ~1 minute. Your site will be live at `https://<username>.github.io/<repo>/`.

### Custom domain (optional)
In **Settings → Pages → Custom domain**, enter your domain and follow the DNS instructions. This will add a `CNAME` file to the repo.

## Notes
- The page loads two web fonts (IBM Plex Sans, Spectral) from Google Fonts at runtime, so visitors need an internet connection for the intended typography; it falls back to system fonts otherwise.
- All images are local in `assets/` — nothing else is fetched from external servers.
