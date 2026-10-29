# Drifan Audio — holding website

A static, dependency-free website. Open `index.html` locally to preview.

## Brand artwork

`assets/drifan-logo.svg` is a **temporary typographic placeholder**, not the previously approved Drifan/Eth logo. Replace it with the approved SVG, keeping the filename unchanged. The current favicon is also temporary.

## GitHub Pages

1. Create a public repository in the intended GitHub account or organisation (for example `drifanaudio-website`).
2. Commit all files in this folder to the repository root on `main`.
3. Repository Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
4. In Pages settings, set Custom domain to `www.drifanaudio.co.uk` and save.
5. At Porkbun, configure `www` CNAME to `<your-github-account-or-org>.github.io` (use your **actual** GitHub owner name).
6. To make `drifanaudio.co.uk` work too, add these four A records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
7. Remove only conflicting web/parking A, AAAA, or CNAME records. Do **not** delete MX, SPF, DKIM, DMARC or Google Workspace verification records.
8. Wait for DNS and certificate provisioning, then enable **Enforce HTTPS** in Pages settings.

GitHub's official custom-domain documentation is at https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Editing

All content is in `index.html`; appearance is in `styles.css`. No build step, JavaScript frameworks or third-party services are required.

## Branding

The logo and favicon were extracted from the supplied outlined Drifan Tested label SVG. The original label is not modified. The DRIFAN lettering and Eth mark are vector paths, requiring no external fonts.
