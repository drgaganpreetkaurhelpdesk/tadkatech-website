# TadkaTech — Marketing Landing Page

Static landing page for **TadkaTech**, the all-in-one restaurant operating system.

- **Live site:** https://tadkatech.in
- **Hosting:** GitHub Pages (custom domain via `CNAME`)
- **Source:** single self-contained `index.html` (no build step, no dependencies)

## How it's served

GitHub Pages serves the `main` branch root. The `CNAME` file binds the apex domain
`tadkatech.in`. DNS is managed at Hostinger (A/AAAA records → GitHub Pages IPs,
`www` CNAME → `drgaganpreetkaurhelpdesk.github.io`).

## Editing

Edit `index.html` and push to `main` — GitHub Pages redeploys automatically within a minute.

> This repo is intentionally separate from the (private) application repo so the public
> marketing site shares none of the product source. When the app VPS is live, `Sign in`
> points at `https://app.tadkatech.in`.
