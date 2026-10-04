# eclintrial.com

Official marketing website for eClintrial. Static HTML/CSS/JS, so there is no build step.

## Run locally
```bash
python3 -m http.server 8080   # then open http://localhost:8080
```

## Structure
- `index.html`: homepage (hero, platform, solutions, compliance, about, contact)
- `privacy.html`, `terms.html`: legal templates (**have them reviewed by counsel**)
- `404.html`, `robots.txt`, `sitemap.xml`
- `css/styles.css`, `js/main.js`, `assets/logo.svg`

## Before launch
- Replace placeholder stats, testimonials and company story with real content.
- Set `FORM_ENDPOINT` in `js/main.js` (e.g. Formspree, HubSpot, or your own API). Until you do, the form only shows a success message and nothing is sent.
- Confirm the contact email addresses.

## Deploy
Works on any static host: Netlify, Vercel, Cloudflare Pages, GitHub Pages, or S3 + CloudFront.
