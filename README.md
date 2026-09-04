# website

The official website of Makerion Labs, built with [Astro](https://astro.build) + Tailwind CSS.

## Development

```sh
npm install
npm run dev
```

## Build

```sh
npm run build
npm run preview
```

Deploys as a static site — output goes to `dist/`. Configured for Cloudflare Pages
(build command `npm run build`, output directory `dist`).

## To update before launch

- [x] Confirm production domain and update `site` in `astro.config.mjs` — `makerionlabs.com` confirmed
- [x] Replace placeholder contact email in `src/components/Contact.astro` — `hello@makerionlabs.com` forwarding configured
- [ ] Replace placeholder products in `src/components/Products.astro` (Monobase — confirm real link/description when it's ready to show)
- [ ] Add real social links in `src/components/Footer.astro`

## Analytics

Cloudflare Web Analytics is enabled in automatic mode (Dashboard → Analytics & Logs →
Web Analytics) — no tracking script needed in the codebase.
