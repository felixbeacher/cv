# Felix Beacher, PhD — Personal Website & ATS-Optimized CV

A responsive static portfolio website and ATS-optimized printable CV for **Felix Beacher, PhD** (Clinical Data Scientist & Medical AI Strategist).

## Contents
- `index.html`, `styles.css`, `script.js` — Main portfolio website with interactive publication filtering (`All`, `Medical AI`, `Clinical Trials`, `Neurology`, `Regulatory`), career timeline, and contact section.
- `cv.html` — Single-column, ATS-optimized printable CV with `@media print` styling for clean PDF export.
- `Felix_Beacher_CV_ATS.md` — Plain-text/Markdown source of the ATS-optimized CV.
- `CV_REVIEW.md` — Detailed CV audit and ATS optimization report.

## Preview Locally
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

## Push to GitHub & Enable GitHub Pages
1. Install `git` if not already installed:
   ```bash
   sudo apt update && sudo apt install -y git
   ```
2. Re-authenticate the GitHub CLI (`gh`):
   ```bash
   gh auth refresh -h github.com
   ```
3. Initialize the repository, commit, and push to GitHub:
   ```bash
   git init -b main
   git add .
   git commit -m "Initial commit: Felix Beacher PhD website and ATS-optimized CV"
   gh repo create felixbeacher.github.io --public --source=. --remote=origin --push
   ```
   *(Or replace `felixbeacher.github.io` with any repository name and enable GitHub Pages in **Settings → Pages → Deploy from branch `main`**.)*
