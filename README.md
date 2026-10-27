# Timeshare Calculators Website

Marketing, support, and privacy pages for **Timeshare Calculators with AI**.

The site is a buildless static project served from `docs/`.

## Local preview

From the repository root:

```sh
python3 -m http.server --directory docs 8000
```

Then open `http://localhost:8000`.

## Cloudflare Pages

Connect this repository, use `main` as the production branch, leave the build command blank, and set the output directory to `docs`.
