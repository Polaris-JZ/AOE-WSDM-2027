# AOE@WSDM 2027 Workshop Website

Static website for the Workshop on Agent-in-the-Loop Optimization for E-commerce AI Systems (AOE) at WSDM 2027.

## Current content source

Workshop details, scope, program, speaker status, submission categories, and organizer biographies are synchronized with `../paper/main.tex` and its `aoe2027/Section/` inputs as of October 8, 2026.

## Local preview

Open `index.html` directly in a browser, or serve the repository root:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Upload the repository files to the default branch.
2. Open **Settings → Pages** in the GitHub repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the default branch and the `/ (root)` folder, then save.

The site is self-contained and does not require a build step. New public portrait sources are recorded in `assets/photo-sources.txt`.
