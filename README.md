# Anvesh Labs — website

Source for [anveshlabs.com](https://anveshlabs.com): a static, single-page site for Anvesh Labs and its apps (Sarav, Deskmate).

## Files

- `index.html` — the home page (HTML, CSS and a little JS in one file), with SEO meta tags and schema.org structured data
- `privacy.html`, `terms.html` — Privacy Policy and Terms of Service (served at `/privacy`, `/terms`)
- `delete-account.html` — account deletion page required by Google Play (`/delete-account`)
- `support.html` — help and FAQ, used as the store support URL (`/support`)
- `assets/legal.css` — shared styles for the inner pages
- `robots.txt`, `sitemap.xml` — for search engines
- `vercel.json` — clean URLs and caching headers

## URLs for Play Console

| Field | URL |
| --- | --- |
| Privacy policy | https://anveshlabs.com/privacy |
| Account deletion (Data safety) | https://anveshlabs.com/delete-account |
| Website / support | https://anveshlabs.com/support |

Highlighted `[PLACEHOLDERS]` in the legal pages must be filled in before submission.

## Deploy on Vercel

1. Import this repo in Vercel (Add New → Project).
2. Framework preset: **Other**. No build command, output directory: root.
3. Add the domain `anveshlabs.com` (and `www.anveshlabs.com` redirecting to it) under Settings → Domains, then update DNS at your registrar as Vercel shows.

Every push to `main` deploys automatically.

## Still to add

- `og-image.png` (1200×630) and `logo.png` — referenced in the page's meta tags
- `app-ads.txt` — once you have an AdMob publisher ID
