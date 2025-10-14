Demo

- https://kaden175ck.github.io/Noted/ (auto-redirects to #/)

Overview

- Noted is a simple React notes app with tags and filtering.
- Data persists in localStorage. Deployed on GitHub Pages (HashRouter).

Tech

- Vite + React + TypeScript
- React Router (HashRouter)
- React Bootstrap, react-select
- gh-pages for deployment

Dev

- Node 18+ recommended
- Install: npm ci
- Run: npm run dev
- Open: http://localhost:5173/Noted/#/ (auto-redirect from /Noted)

Build & Deploy

- Build: npm run build
- Deploy: npm run deploy (publishes dist to gh-pages branch)
- GitHub Settings → Pages → Source: gh-pages (root)

Notes

- vite.config.ts uses base: '/Noted/'
- If you see a blank page, ensure the URL includes #/ and clear localStorage keys NOTES/TAGS.

<!-- npm i react-bootstrap bootstrap react-router-dom react-select uuid   react-markdown-->
