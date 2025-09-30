# ArtHub Legal Pages (GitHub Pages)

This repo hosts the public legal pages for **arthub.world** (ArtHub World).

## Files
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `data-deletion.html` — User Data Deletion instructions

> Update contact details inside the files if needed: `support@arthub.world`.

## Publish on GitHub Pages (free)
1. Create a **public** repo (e.g., `arthub-legal`).
2. Add the three HTML files at the repo root.
3. Go to **Settings → Pages**:
   - **Build and deployment**: Source = `Deploy from a branch`
   - Branch = `main` (or `master`), Folder = `/root`
   - Save — GitHub will give you a URL like `https://YOURUSER.github.io/arthub-legal/`

Your URLs will then be:
- `https://YOURUSER.github.io/arthub-legal/privacy.html`
- `https://YOURUSER.github.io/arthub-legal/terms.html`
- `https://YOURUSER.github.io/arthub-legal/data-deletion.html`

## Optional: Use your domain `https://legal.arthub.world`
Using a subdomain keeps your main site free and is simpler for DNS.

1. In **Settings → Pages**, set **Custom domain** to `legal.arthub.world`.
2. In your domain DNS, add a **CNAME** record:
   - **Host/Name**: `legal`
   - **Value/Target**: `YOURUSER.github.io`
3. Commit a file named `CNAME` in the repo root containing exactly:
   ```
   legal.arthub.world
   ```
4. Wait for DNS to propagate, then your URLs will be:
   - `https://legal.arthub.world/privacy.html`
   - `https://legal.arthub.world/terms.html`
   - `https://legal.arthub.world/data-deletion.html`

## Paste into Facebook App settings
- **Privacy Policy URL**: `https://legal.arthub.world/privacy.html`
- **Terms of Service URL**: `https://legal.arthub.world/terms.html`
- **User Data Deletion**: `https://legal.arthub.world/data-deletion.html`

All pages are HTTPS, public, and platform‑policy friendly.
