# Deploy the landing page to Vercel

This repository contains a standalone Next.js landing app.

## Vercel project settings

When importing the repository into Vercel, use these settings:

- **Root Directory:** `.` (the repository root)
- **Framework Preset:** Next.js (auto-detected)
- **Build Command:** leave the default (`next build`)
- **Output Directory:** leave the default
- **Install Command:** leave the default

Vercel uses the Next.js runtime; no static export or custom server is needed. The repository does not require monorepo workspace packages.

For local production-mode checks, run `npm install`, `npm run build`, then `npm start`.
