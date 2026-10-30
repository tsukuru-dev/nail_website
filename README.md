# KT Nails & Spa

A responsive Astro website for the salon at 128 Tolworth Broadway.

## Development

Requires Node.js 22.12 or newer.

```sh
npm install
npm run dev
```

Open the local URL printed by Astro (normally http://localhost:4321).

```sh
npm run build
npm run preview
```

The production site is generated in `dist/` and can be deployed to any static host.

## Content

- `src/pages/index.astro`: page content, treatments, Instagram and directions links.
- `src/styles/global.css`: responsive styling and colour palette.
- `public/images/manicure.png`: AI-generated illustrative manicure image, not a photograph of the salon's work. Replace it with an original salon photo when available. The salon interior and colour swatches are CSS illustrations.

The name, address and Instagram handle come from the provided reference screenshots. Opening hours and prices have intentionally not been invented. Booking links open the salon's Instagram profile for an enquiry; there is no booking backend or automatic appointment confirmation. Confirm treatment details with the salon before public launch.
