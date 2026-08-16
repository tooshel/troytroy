troytroy
========

Troy's Site

This site was made as a tribute to Troy. Not a lot of traffic but I don't ever want to forget so now it's on GitHub pages and since it's a static site it's easy to generate and host anywhere.

Sheldon

How it's set up
---------------

- Static Jekyll site, built and served by GitHub Pages from the `main` branch (root).
- Custom domain `www.troytroy.com` via the `CNAME` file; DNS is on Cloudflare with `www` a DNS-only CNAME to `tooshel.github.io` and the apex redirecting to `www`. HTTPS is enforced with a GitHub-provisioned Let's Encrypt certificate.
- Layout lives in `_layouts/default.html`, nav in `_includes/main-nav.html`, styles in `css/troy.css` (print styles included via `@media print`).
- The animated train (`images/darkmovingtrain2.gif`) is original from ~2003 and stays.
