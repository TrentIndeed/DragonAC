# Dragon A/C — HVAC landing page

A fast, conversion-focused landing page for **Dragon A/C**, a North Texas HVAC
business. Hand-written static site (HTML/CSS) deployed on **Cloudflare** via Wrangler.

🔗 **Live:** https://dragonac.com

## Highlights
- **Conversion-first layout** — sticky call-to-action buttons, a lead form, and a mobile "tap to call" bar.
- **No backend, nothing to leak** — plain HTML/CSS; the lead form opens a pre-filled email rather than posting to a server.
- **Deployed on Cloudflare** — served as static assets through a Worker (`wrangler.jsonc`).

## Stack
Static HTML + CSS · Cloudflare Workers / Wrangler

## Local preview / deploy
```
npx wrangler dev      # preview locally
npx wrangler deploy   # publish to Cloudflare
```

## License
MIT — see [LICENSE](LICENSE).
