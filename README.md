# LAD ASSOCIATION — React + Vite Insurance App

This repository is a production-ready responsive web application scaffolded with React (Vite), Tailwind CSS, Firebase Authentication & Firestore, Framer Motion, and other utilities. It's ready to be deployed to Vercel.

Quick start

1. Copy `.env.example` to `.env` and fill Firebase credentials and `VITE_ADMIN_EMAIL`.

2. Install dependencies

```bash
npm install
```

3. Run locally

```bash
npm run dev
```

4. Build production

```bash
npm run build
```

5. Preview production build

```bash
npm run preview
```

Deploy to Vercel

- Create a new Vercel project and link this repo.
- Add the environment variables from `.env` to Vercel dashboard.
- Set the build command to `npm run build` and the output directory to `dist`.

Project structure

- `src/components` — Reusable UI components
- `src/pages` — Route pages
- `src/layouts` — App layouts
- `src/firebase` — Firebase initialization and helpers
- `src/contexts` — Auth context

Notes

- The admin route is protected and checks if the logged-in user's email matches `VITE_ADMIN_EMAIL`.
- The Policy Enquiry form saves documents to Firestore collection `enquiries`.
