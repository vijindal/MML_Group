# MML Group

Website of the **Materials Modeling Lab**, Department of Metallurgical Engineering, IIT (BHU) Varanasi.

Static HTML/CSS/JS site, deployed automatically to GitHub Pages via a GitHub Actions workflow on every push to `main`.

## Structure

- `index.html` — home page
- `Research.html`, `Publications.html`, `News.html`, `People.html`, `Openings.html`, `Lab_facilities.html`, `Teaching.html`, `Contact_Us.html` — main site pages
- `Optimization.html`, `computational_thermodynamics.html`, `gibbs_cvm.html`, `data.html`, `user_charges.html`, `charpy.html` — research/facility sub-pages
- `header.html`, `navbar.html`, `footer.html` — shared page fragments
- `style.css`, `style.js` — site styling and scripting
- `image/` — site images and logos
- `pdf/` — publications and downloadable PDFs
- `.github/workflows/static.yml` — GitHub Pages deployment workflow

## Development

The site is plain static HTML — open any `.html` file directly in a browser, or serve the folder locally, e.g.:

```bash
npx serve .
```

## Deployment

Pushing to `main` automatically deploys the site to GitHub Pages (see `.github/workflows/static.yml`).
