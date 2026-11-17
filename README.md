# Anvesh Labs — website

Source for [anveshlabs.com](https://anveshlabs.com): a static, single-page site for Anvesh Labs and its apps (Sarav, SchoolDeck).

## Files

- `index.html` — the whole site (HTML, CSS and a little JS in one file), with SEO meta tags and schema.org structured data
- `robots.txt`, `sitemap.xml` — for search engines
- `vercel.json` — clean URLs and caching headers

## Deploy on Vercel

1. Import this repo in Vercel (Add New → Project).
2. Framework preset: **Other**. No build command, output directory: root.
3. Add the domain `anveshlabs.com` (and `www.anveshlabs.com` redirecting to it) under Settings → Domains, then update DNS at your registrar as Vercel shows.

Every push to `main` deploys automatically.

## Still to add

- `og-image.png` (1200×630) and `logo.png` — referenced in the page's meta tags
- `/privacy` and `/terms` pages — required before publishing Sarav on the Play Store
