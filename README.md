# Astro Portfolio Scaffold

This project migrates the former Jekyll portfolio for Miguel Alejandro de la Rocha to an Astro + TypeScript foundation. It keeps legacy static assets and content placeholders so the design can be rebuilt iteratively with modern tooling.

## Getting Started

```bash
npm install
npm run dev
```

- `npm run dev` – start the Astro development server.
- `npm run build` – create a production build in `dist/`.
- `npm run preview` – preview the production build locally.
- `npm run check` – type-check Astro components and TypeScript files.
- `npm run lint` – run ESLint across the project.
- `npm run format` – validate Prettier formatting.

## Project Structure

```
/
├── public/               # Static assets preserved from the Jekyll site
├── src/
│   ├── layouts/          # Base layout components
│   ├── pages/            # Route files (.astro)
│   └── styles/           # Shared stylesheets
├── docs/legacy-audit.md  # Inventory of legacy content & assets
├── astro.config.mjs
├── tsconfig.json
└── package.json
```

All legacy images, fonts, and vendor assets now reside under `public/`. The home page (`src/pages/index.astro`) contains placeholder sections that mirror the original site’s structure so you can progressively enhance the design with new Astro components.
