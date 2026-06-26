# Sentivel docs

The public docs for Sentivel, built with [Mintlify](https://mintlify.com) and
deployed to docs.sentivel.com. This repo is the deployed source of truth.

- Prose pages are the `.mdx` files; config is `docs.json`.
- The API reference is generated from the live OpenAPI spec at
  `https://www.sentivel.com/api/v1/openapi.json`.
- Voice + style: see `STYLE.md` and `AGENTS.md`. Every page is written and
  reviewed against them (no AI-tell language).

## Local preview

```bash
npm i -g mint
mint dev   # http://localhost:3000
```

Pushes to `main` deploy automatically via the Mintlify GitHub app.
