# Och

A modern, animated landing page / portfolio-style website.

## Live Demo

https://och-eta.vercel.app/

## Features

- Smooth, responsive UI
- Scroll-based interactions and motion effects
- Reusable, component-driven layout
- Mobile-friendly styling

## Tech Stack

- React
- Vite
- Tailwind CSS
- (Optional/if used) Framer Motion for animations
- (Optional/if used) Locomotive Scroll / smooth scrolling library

## Getting Started

### Prerequisites
- Node.js (LTS recommended)
- npm (or yarn/pnpm)

### Install & Run

```bash
npm install
npm run dev
```

Open the URL shown in the terminal (usually `http://localhost:5173`).

## Scripts

```bash
npm run dev      # start development server
npm run build    # create production build
npm run preview  # preview production build locally
```

## Project Structure (typical)

```text
.
├─ src/
│  ├─ components/
│  ├─ assets/
│  ├─ App.jsx
│  └─ main.jsx
├─ public/
└─ package.json
```

## Deployment

This project is deployed on Vercel:
- Live: https://och-eta.vercel.app/

To deploy your own fork, import the repo into Vercel and use the default Vite settings:
- Build Command: `npm run build`
- Output Directory: `dist`

## License

Add a license if you intend to make this reusable (e.g., MIT).
