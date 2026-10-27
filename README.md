# Timeshare Calculators Website

Marketing, support, and privacy pages for **Timeshare Calculators with AI**.

The site is a buildless static project served from `docs/`.

## Local preview

From the repository root:

```sh
python3 -m http.server --directory docs 8000
```

Then open `http://localhost:8000`.

## Cloudflare Workers

Connect this repository to Workers Builds and use `main` as the production branch. Leave the build command blank and use `npx wrangler deploy` as the deploy command. Static assets are configured in `wrangler.jsonc` and served from `docs/`.
