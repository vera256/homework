# Homework

Website: https://homework.minimum.se

This repository contains a static website. Edit `index.html` or add HTML, CSS,
JavaScript, and other assets in the repository root.

## GitHub Pages setup

In repository **Settings → Pages**, configure:

- Source: **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Custom domain: **homework.minimum.se**
- Enable **Enforce HTTPS** once GitHub provisions the certificate.

DNS must contain a CNAME record from `homework.minimum.se` to
`vera256.github.io`. The `CNAME` file preserves the site's custom domain.

Once Pages is enabled, pushes to `main` automatically publish the website.
