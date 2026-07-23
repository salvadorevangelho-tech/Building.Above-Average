# Building Above Average — Life OS landing page

## Run locally
npm install
npm run dev

## Deploy
1. Push this folder to a new GitHub repo
2. Import the repo in Vercel (vercel.com/new)
3. Vercel auto-detects Vite, click Deploy
4. In Vercel: Settings > Domains > add buildingaboveaverage.com
5. Update your domain's DNS as Vercel instructs (usually one CNAME/A record)

## Before going live
- Open src/App.jsx
- Replace href="#checkout-link" with your real Lemon Squeezy checkout URL (2 places)
- Replace href="#newsletter-signup-link" with your real Lemon Squeezy signup form URL (5 places)
- Add public/favicon.png (512x512) and public/og-image.png (1200x630)
