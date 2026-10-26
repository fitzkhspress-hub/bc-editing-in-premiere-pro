# From footage to broadcast

A beginner Adobe Premiere Pro walkthrough for a 45–60 second school news package. Eight steps, with an 8½-minute reading schedule. Actual editing, watching the complete sequence, and rendering take additional time.

## Deploy to GitHub Pages

1. Unzip the download on your computer.
2. In your GitHub repository, upload **the contents** of `premiere-broadcast-github-pages` to the repository root. Keep `index.html`, `styles.css`, `app.js`, and `walkthrough.txt` together; include `.nojekyll` if available.
3. Commit the files to `main`.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose **main** and **/ (root)**, then **Save**.
6. Wait for GitHub to finish deploying and use the site link shown in Pages settings.

If the repository already contains a site, put these files in a `premiere/` folder and visit its `/premiere/` path after deployment. Preserve the existing Pages publishing settings.

## Included

- Responsive, accessible static page with eight navigable lessons and teaching diagrams
- Browser-local progress; reset available; no account or data submission
- Printable complete guide and downloadable text delivery checklist
- Full text fallback in `walkthrough.txt`
- Links to Adobe documentation, checked October 26, 2026

No build, dependencies, external fonts, analytics, API keys, or server are needed. Works under a GitHub Pages repository subpath. Requires JavaScript for the interactive steps; the complete text fallback works without it. Browser printing can save a PDF.

All artwork is original CSS illustration, not an Adobe interface screenshot. Uses current Properties-panel terminology with a note for older releases. A practice H.264 MP4 is distinguished from a station master, which must meet the receiving station's specifications.
