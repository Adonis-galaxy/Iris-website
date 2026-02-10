# Iris — Project Page

Project page for **Iris: Integrating Language into Diffusion-based Monocular Depth Estimation** (CVPR 2026).

## View the page

- **Local:** open `index.html` in a browser, or run:
  ```bash
  python3 -m http.server 8000
  ```
  then visit `http://localhost:8000`.

- **GitHub Pages:** push this folder to a GitHub repo, then:
  1. Repo → **Settings** → **Pages**
  2. **Source:** Deploy from a branch
  3. **Branch:** `main` (or your default branch), **Folder:** `/ (root)`
  4. Save. The site will be at `https://<username>.github.io/<repo>/`.

## Contents

- `index.html` — single-page project site (abstract, teaser, pipeline, results, BibTeX).
- `assets/` — figure PDFs from the paper (teaser, pipeline, visualizations, convergence).

## Optional: PNG figures

For wider browser support (e.g. some mobile), you can export PDFs to PNG and add them as `assets/teaser.png`, `assets/pipeline.png`, etc. The HTML already uses them as fallback inside each `<object>` tag.

## Links to update

In `index.html`, replace the placeholder `#` links when ready:

- **Paper (PDF):** arXiv or CVPR Open Access URL.
- **Supplementary:** PDF or appendix URL.
- **Code:** GitHub repo or “Coming Soon”.
- **Generated Text Data:** dataset or “Coming Soon”.
