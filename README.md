# RockLabs Portfolio v2

Modern, responsive portfolio starter for **RockLabs / Rocky**, built with React + Vite.

## Features
- Dark and light theme toggle
- Responsive mobile navigation
- Searchable project gallery with six categories, featured-only toggle, reset filters, and project JSON export
- Project detail modals with descriptions, status, tags, and email enquiry action
- Quick navigation command palette (`Ctrl/Cmd + K`) and `/` to focus project search
- Share portfolio using Web Share API when supported, otherwise copies the URL
- Copy-email action, toast notifications, service cards, timeline, workflow, and toolkit
- SEO metadata, Open Graph basics, favicon, `robots.txt`, `sitemap.xml`
- Reduced-motion support and Vercel SPA rewrite config

## Run locally
Install Node.js 20+ and run:

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

## Important: personalize before publishing
1. Replace `hello@rocklabs.us` with the email address you actually use.
2. Replace the generic GitHub URL in `src/main.jsx` with your real profile.
3. Edit the project list at the top of `src/main.jsx`. The project entries are portfolio descriptions, not proof that every project is complete or publicly available. Adjust statuses and wording honestly.
4. Add your real project links/screenshots and an actual CV file if desired.
5. The contact form is email-link based (no backend or message storage is included).
6. The project JSON export exports the current project metadata; it does not upload anything to a server.

## Deploy to Vercel
1. Push this folder to GitHub.
2. Import the repository into Vercel.
3. Build command: `npm run build`
4. Output directory: `dist`
5. Add `rocklabs.us` and `www.rocklabs.us` under Project Settings → Domains and follow Vercel's DNS instructions.

The website source is prepared for deployment, but it has not been deployed or connected to the domain by this package.
