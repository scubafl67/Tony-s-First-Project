# CIPGuard™ Landing Page

Marketing landing page for CIPGuard™, built with [React](https://react.dev) and
[Vite](https://vite.dev). Styled with [Tailwind CSS](https://tailwindcss.com).

## Requirements

- Node.js 20+
- npm

## Getting started

```bash
npm install      # install dependencies
npm run dev      # start the local dev server (Vite, with HMR)
```

## Scripts

| Command           | Description                                  |
| ----------------- | -------------------------------------------- |
| `npm run dev`     | Start the Vite dev server with hot reload    |
| `npm run build`   | Produce a production build in `dist/`        |
| `npm run preview` | Serve the production build locally           |
| `npm run lint`    | Run ESLint over the project                  |

## Deployment

The site is deployed on [Netlify](https://www.netlify.com). Build settings are
defined in [`../netlify.toml`](../netlify.toml) at the repository root:

- **Base directory:** `cipguard-landing`
- **Build command:** `npm run build`
- **Publish directory:** `dist` (resolved relative to the base directory)

Pushes to the connected branch trigger an automatic Netlify build and deploy.
