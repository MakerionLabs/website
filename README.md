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

- [ ] Confirm production domain and update `site` in `astro.config.mjs`
- [ ] Replace placeholder contact email in `src/components/Contact.astro`
- [ ] Replace placeholder products in `src/components/Products.astro`
- [ ] Add real social links in `src/components/Footer.astro`
