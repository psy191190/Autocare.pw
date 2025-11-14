# autocare.pw — site placeholder

This repository currently contains a minimal static placeholder site intended for GitHub Pages.

What this does:
- index.html — placeholder homepage
- styles.css — minimal styling
- CNAME — contains `autocare.pw` so GitHub Pages will serve the custom domain
- .nojekyll — disables Jekyll so files/folders starting with `_` are served

If you want me to:
- Push your existing site build (paste a zip or list of files), or
- Publish to IPFS/Unstoppable instead,

tell me which and I will update the repo accordingly.

DNS notes (for GitHub Pages with a custom apex domain):
- Add A records:
  185.199.108.153
  185.199.109.153
  185.199.110.153
  185.199.111.153
- Add a CNAME for `www` -> `psy191190.github.io` (optional, if you want www to work)
- Remove any registrar-level URL forwarding/redirects so DNS records are used directly.
