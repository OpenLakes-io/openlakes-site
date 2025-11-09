# OpenLakes.io Website

Marketing landing page for the OpenLakes.io lakehouse offerings and training packages.

## Local preview

```bash
python3 -m http.server --directory openlakes-site 8000
```

Then open <http://localhost:8000>.

## Deploying to GitHub Pages

1. Push the contents of `openlakes-site/` into a public repository (see suggestions in the main instructions).
2. In repository settings, enable GitHub Pages and select the `main` branch with the `/` root.
3. The site will deploy to `https://<username>.github.io/<repo>/` or to the apex if you use a custom domain.
