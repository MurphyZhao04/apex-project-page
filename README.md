# APEX Project Website

This folder contains the static project page for:

**APEX: Adaptive Policy Execution for Precise Manipulation**

The page is adapted from the Nerfies academic project page template and can be hosted directly with GitHub Pages.

## Local Preview

Open `index.html` in a browser, or run a small static server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages URL

https://murphyzhao04.github.io/apex-project-page/

## GitHub Pages Publishing

This site is published from the `main` branch of `MurphyZhao04/apex-project-page`.

If republishing from another checkout, point the local folder to the repository:

```bash
git remote add origin https://github.com/MurphyZhao04/apex-project-page.git
```

Then commit and push:

```bash
git add .
git commit -m "Create APEX project website"
git branch -M main
git push -u origin main
```

## Main Files

- `index.html`: project page content
- `static/css/index.css`: project-specific styling
- `static/images/apex/`: rendered figures from the paper
- `static/videos/apex/`: real-robot rollout videos
- `static/pdfs/apex-paper.pdf`: paper PDF
- `.nojekyll`: tells GitHub Pages to serve the static files directly
