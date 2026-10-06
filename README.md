# The Runner Number 2 — support site

Static site (no build step), styled like the Number 1 page.

- `index.html` — support page: hero with screenshots, contact card, FAQ, app info
- `privacy-policy.html` — privacy policy
- `styles.css` — shared styles
- `images/` — logo, favicon, 4 screenshots

## Before publishing
1. In `index.html`, replace the "Coming soon to the App Store" badge with your real App Store link once the app is live.
2. Re-read `privacy-policy.html` and update it if the app changes (new SDKs, analytics, accounts…).
3. The contact address is `randommobileapp@gmail.com` (same as the Number 1 site) — change it in both pages if needed.

## Publish with GitHub Pages
Create a repo (e.g. `therunnernumber2_page`), upload these files to the root, then Settings → Pages → deploy from `main` / root.
The page will be at `https://<user>.github.io/therunnernumber2_page/`; use `.../privacy-policy.html` as the Privacy Policy URL in App Store Connect and the main URL as the Support URL.
