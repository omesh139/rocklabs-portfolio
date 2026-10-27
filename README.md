# RockLabs Portfolio — Nebula v4 — Visual Edition

A bold, responsive developer portfolio built with React, Vite, and Lucide icons. Styled with a near-black canvas, neon-lime accents, atmospheric grids, orbital motion, elevated project cards, and keyboard-friendly interactions.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

Vite outputs the production site to `dist/`.

## Deploy to Vercel

1. Push the contents of this folder to your GitHub repository.
2. Import the repository in Vercel.
3. Framework preset: **Vite**.
4. Build command: `npm run build`.
5. Output directory: `dist`.

The repository includes `vercel.json` with these settings. Keep your dependencies current and commit `package-lock.json` after running `npm install` locally for reproducible builds.

## Features

- Responsive layout and mobile navigation
- Animated hero orbital / studio panel
- Searchable and filterable project grid
- Project detail dialogs
- Light/dark theme toggle
- Keyboard quick navigation (`Ctrl/Cmd + K`) and `/` to focus project search
- Share and copy-email actions
- Reduced-motion support, visible keyboard focus, and skip-to-content link

## Customization

Edit project entries, skills, and service descriptions in `src/main.jsx`. Visual tokens and animations live in `src/styles.css`. Metadata lives in `index.html`.

## New in Nebula v4

- 10 bundled, optimized WebP concept-art images (no external image hosts).
- Image-backed project cards and detailed project modal illustrations.
- An editorial three-image RockLabs creative showcase section.
- Atmospheric hero artwork with interactive glow, while retaining the existing orbital component.
- Responsive image gallery, image zoom/hover polish, and reduced-motion support.

**Artwork disclosure:** Project pictures are AI-assisted illustrations for portfolio presentation. They are not claimed as authentic product screenshots. Replace each `public/images/*.webp` with real project screenshots when available.

The email address in this portfolio is `hello@rocklabs.us` — update it in `src/main.jsx` if that mailbox is not active.
