# Itrino website

Static website for Itrino. No build step or framework is required.

## Files
- `index.html` — homepage and SEO metadata
- `styles.css` — site styling
- `assets/` — favicon and social sharing artwork
- `robots.txt` / `sitemap.xml` — search-engine discovery
- `site.webmanifest` — browser/PWA metadata
- `404.html` — GitHub Pages fallback page
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment

## Deploy with GitHub Pages
1. Create a GitHub repository and place these files at the repository root.
2. Push to the `main` branch.
3. In **Settings → Pages → Build and deployment**, select **GitHub Actions**.
4. The included workflow deploys the site after every push to `main`.

## Before connecting a production domain
The SEO metadata currently uses `https://itrino.ai/`. If the final domain differs, replace `https://itrino.ai` in `index.html`, `robots.txt`, and `sitemap.xml` before launch.

No `CNAME` file is included intentionally. Add the custom domain in GitHub Pages settings after DNS is configured; GitHub can then create/manage the domain association.

## Contact address
The homepage currently uses `medatlas@itrino.ai`. Confirm or replace this address before public launch.
