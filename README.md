# Test Product Website

Minimal GitHub Pages demo for QR code + Digital Link URI behavior.

## Goal

- Root page: `/` (served by `index.html`)
- Digital Link path: `/09357645011115`
- Behavior: `/09357645011115` loads a dedicated page that immediately forwards to `/`

This approach works on GitHub Pages without wildcard server redirects.

## Files

- `index.html` - simple product page with dummy data
- `09357645011115/index.html` - entry page for the Digital Link path

## Publish on GitHub Pages

1. Push these files to your repository default branch.
2. In repository settings, open **Pages**.
3. Set source to your branch root (for example: `main` + `/ (root)`).
4. Save and wait for deployment.

## Test URLs

- `https://domainName.github.io/`
- `https://domainName.github.io/09357645011115`

Both should end up showing the product page content.
