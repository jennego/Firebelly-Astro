# 🔥 Firebelly Farm

> Where Days Smell Like Hay & Happiness

A hobby farm website built with [Astro](https://astro.build).

## Project Structure

```
firebelly-farm/
├── public/
│   └── sunrise_mares_24.jpg   ← hero photo
├── src/
│   ├── components/
│   │   ├── Nav.astro
│   │   ├── Hero.astro
│   │   ├── SummerCamp.astro
│   │   ├── Animals.astro
│   │   ├── VisitUs.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
└── package.json
```

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Customisation

- **Content & dates**: Edit the data arrays at the top of each `.astro` component
- **Colours**: The palette uses `#c0390b` (red), `#e8560a` (orange), and `#ffd580` (gold accent) — find/replace to retheme
- **Hero photo**: Replace `public/sunrise_mares_24.jpg` with any image; update the `src` in `Hero.astro`
- **Fonts**: Loaded from Google Fonts in `BaseLayout.astro` — swap `Playfair Display` / `Nunito` as desired
