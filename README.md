# AURENTUM — Exclusive Perfumes

A React + Vite e-commerce frontend for the AURENTUM perfume brand.

## Run locally

```bash
npm install
npm run dev
```

Open the printed local URL (usually `http://localhost:5173`).

## Build for production

```bash
npm run build
npm run preview   # optional: preview the production build locally
```

The production files are written to `dist/`.

## Editing your store

- **Products**: edit `src/data/products.js`. Every field is documented at
  the top of the file. Replace the `PLACEHOLDER` text and add real photos
  to `public/products/` (reference them from the `images` array).
- **Business details** (WhatsApp number, email, phone, address, socials,
  shipping rates): edit `src/data/siteConfig.js`.
- **Logo**: your uploaded artwork lives in `public/brand/`. Swap the files
  there (keep the same filenames) to update the logo everywhere.

## What's real vs. placeholder

- Cash on Delivery and a WhatsApp order flow are fully functional.
- eSewa/Khalti and other online payments are **not** connected — the
  checkout page says so explicitly. Don't remove that note until you've
  wired up a real payment integration.
- Product photography uses elegant line-art placeholders until you add
  real photos — nothing is broken, it's a deliberate stand-in.
- All product prices, descriptions, and fragrance notes are placeholder
  content flagged with `isPlaceholder: true` — replace with real,
  factual information before launch.

## Deploying to Cloudflare Pages (free)

See the deployment steps provided with this project, or:
https://developers.cloudflare.com/pages/framework-guides/deploy-a-vite-project/
