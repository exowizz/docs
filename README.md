# Exo documentation

Public docs for [Exo](https://exowizz.com): the Laravel package that exposes Eloquent resources and webhooks for Zapier, Make, n8n, and similar platforms.

Content lives in MDX pages; site configuration is in `docs.json`. Branding uses the Exo palette. Logos and favicon are copied from the Laravel app’s `public/creatives/svg/` into `docs/` with matching names: `logo-light.svg` → `logo/light.svg`, `logo-dark.svg` → `logo/dark.svg`, `favicon.svg` → `favicon.svg`.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint), then from this directory (where `docs.json` is):

```bash
npm i -g mint
mint dev
```

Open `http://localhost:3000` for a local preview.

## AI-assisted writing

Optional: add Mintlify’s skill for component reference and writing standards:

```bash
npx skills add https://mintlify.com/docs
```

## Publishing

If this repo is connected to Mintlify, pushes to the default branch deploy automatically. See [Mintlify documentation](https://mintlify.com/docs) for GitHub app setup and troubleshooting (`mint update`, valid `docs.json`, etc.).
