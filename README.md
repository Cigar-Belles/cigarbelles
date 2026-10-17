# Philly Cigar Belles

The site for phillycigarbelles.com. A single static page with no build step.

## Files
- `index.html`: the page (styles are inline)
- `assets/belles.jpg`: hero image
- `assets/og.jpg`: share preview image
- `assets/favicon.svg`: browser icon
- `CNAME`: custom domain for GitHub Pages

## Before launch
1. The form posts to Formspree (form xeaenwnb).
2. Fill in Kira's last name and both founder bios.

## Publish on GitHub Pages
1. Push these files to the repo's `main` branch.
2. Go to Settings › Pages, and set the source to deploy from `main` at `/ (root)`.
3. In GoDaddy DNS for phillycigarbelles.com, add:
   - Four `A` records for `@`, pointing to 185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153
   - A `CNAME` record for `www` pointing to `<your-github-username>.github.io`
4. Back in Settings › Pages, tick **Enforce HTTPS** once the certificate is issued.
5. Forward cigarbelles.com and phlcigarbelles.com to https://phillycigarbelles.com in GoDaddy.
