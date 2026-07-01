# Bloom Website / Legal Pages

Static website for Bloom, hosted with GitHub Pages and intended for `https://bloomapp.au`.

## Pages

- `/` — Home
- `/privacy/` — Privacy Policy
- `/terms/` — Terms of Service
- `/support/` — Support
- `/delete-account/` — Account deletion instructions required by Google Play

## Project structure

```text
bloom-legal/
├── index.html
├── privacy/index.html
├── terms/index.html
├── support/index.html
├── delete-account/index.html
├── assets/logo.svg
├── assets/favicon.ico
├── styles/main.css
├── scripts/main.js
└── README.md
```

## GitHub Pages deployment

1. Push this repository to GitHub.
2. Open repository **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/root`.
5. Save.
6. GitHub will publish the site to the default GitHub Pages URL.

## Custom domain

After GitHub Pages works, add the custom domain:

```text
bloomapp.au
```

Then update DNS at your domain provider or Cloudflare according to GitHub Pages instructions.

Recommended DNS records for an apex domain are GitHub Pages A records plus a CNAME for `www`.
Use GitHub's latest documentation before changing DNS.

## Google Play URLs

Use these in Google Play Console:

- Privacy Policy: `https://bloomapp.au/privacy/`
- Account deletion URL: `https://bloomapp.au/delete-account/`
- Support URL: `https://bloomapp.au/support/`

## Maintenance

Update legal pages whenever Bloom changes how it collects, stores, processes, shares, or deletes user data.

## Future roadmap

Possible future pages:

- Features
- Pricing
- FAQ
- Blog
- Changelog
- Downloads
- Press Kit
- About
- Contact
