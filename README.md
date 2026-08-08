# VentiQ

Standalone React + Vite version of the VentiQ ICU application.

## Goal of this build

This version is intentionally kept simple so the application UI starts first without Firebase, authentication, or backend configuration blocking startup.

## Run locally

```bash
npm install
npm run dev
```

Then open the URL shown by Vite.

## Production build

```bash
npm run build
npm run preview
```

## Important

- The current application is frontend-only.
- Firebase/backend integration should be added only after confirming this version starts correctly.
- Do not commit `.env` files containing secrets.
