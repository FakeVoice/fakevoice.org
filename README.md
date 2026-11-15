# fakevoice.org

Static site for https://fakevoice.org, served by GitHub Pages from the `main` branch root.

- `CNAME` sets the custom domain; DNS lives on Cloudflare (apex A/AAAA records to GitHub
  Pages, `www` CNAME to `fakevoice.github.io`, DNS-only so GitHub can issue the certificate).
- Replace `index.html` (and add pages such as `start/`, `safety/`, `for-schools/`) with the
  real site; any static output works. Keep `CNAME` and `.nojekyll`.
