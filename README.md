# Canopy Environments — Website

Marketing site for [Canopy Environments](https://canopyenvironments.com), a commercial floral program service in NYC.

## Structure

```
index.html    – Single-page site (HTML + inline CSS + JS)
images/       – Placeholder directory for hero, mission, and founder photos
CNAME         – Custom domain config for GitHub Pages
```

This is a **static single-file site** — no build tools, no dependencies, no frameworks. Open `index.html` in a browser to preview locally.

## Deployment

### GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages** and set the source to the `main` branch.
3. The `CNAME` file will automatically configure the custom domain.
4. Add DNS records for `canopyenvironments.com` pointing to GitHub Pages ([docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-github-pages)).

### Netlify / Cloudflare Pages
1. Connect the repo — no build command or output directory needed.
2. Set the custom domain to `canopyenvironments.com` in the dashboard.
3. The `CNAME` file is ignored by these platforms (configure domain in their UI instead).

## TODO

- [ ] Replace placeholder gradient images with real photos (see `images/README.md`)
- [ ] Wire the contact form to a backend (Formspree, Netlify Forms, etc.)
- [ ] Add favicon and Open Graph meta images
- [ ] Set up DNS and deploy
