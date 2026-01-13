# 🎨 Och — Modern Animated Landing Page

Status: Live | Responsive | Animated  
Frontend: React | Vite | Tailwind CSS  
Animations: Framer Motion (optional)  
Deployment: Vercel

Och is a modern, animated landing page / portfolio-style website focused on
clean UI, smooth motion, and performance. It uses a component-based React
architecture with Tailwind CSS and optional animation libraries to deliver
a polished, responsive experience across all devices.

---------------------------------------------------------------------

LIVE DEMO

Web: https://och91169.vercel.app/

---------------------------------------------------------------------
## PROJECT STRUCTURE

```text
och/
├─ public/                     # Static assets
│
├─ src/
│  ├─ assets/                  # Images, icons, fonts
│  │
│  ├─ components/              # Reusable UI components
│  │  ├─ Navbar.jsx
│  │  ├─ Hero.jsx
│  │  ├─ About.jsx
│  │  ├─ Projects.jsx
│  │  ├─ Footer.jsx
│  │  └─ Button.jsx
│  │
│  ├─ styles/                  # Global & custom styles
│  │
│  ├─ App.jsx                  # Root component
│  ├─ main.jsx                 # React entry point
│  └─ index.css                # Tailwind CSS imports
│
├─ package.json                # Dependencies & scripts
├─ vite.config.js              # Vite configuration
└─ README.md                   # Project documentation
```

---------------------------------------------------------------------

TECH STACK

Languages & Frameworks
- Frontend: React (JavaScript, ES Modules)
- Build Tool: Vite
- Styling: Tailwind CSS

Libraries & Tools
- Animations: Framer Motion (optional)
- Smooth Scrolling: Locomotive Scroll / Lenis (optional)
- Icons: Lucide / React Icons
- Deployment: Vercel
- Version Control: Git & GitHub

---------------------------------------------------------------------
## HIGH-LEVEL ARCHITECTURE

```text
React + Vite
│
├─ Frontend Application
│
├─ Component-Based UI Layer
│  ├─ Reusable Components
│  ├─ Tailwind CSS Styling
│  ├─ Framer Motion Animations
│  └─ Smooth Scroll (Optional)
│
├─ Static Production Build
│  ├─ dist/
│  ├─ Optimized Assets
│  └─ Minified Bundles
│
└─ Vercel Deployment
   ├─ Global CDN
   └─ Fast Edge Delivery
```

---------------------------------------------------------------------

FEATURES

UI & Design
- Modern portfolio-style landing page
- Clean and minimal layout
- Fully responsive across devices
- Smooth transitions and hover effects

Animations & Interactions
- Scroll-based animations
- Section reveal effects
- Micro-interactions for buttons and links
- Optional smooth scrolling experience

Performance & Developer Experience
- Fast builds with Vite
- Optimized production output
- Reusable, scalable components
- Easy customization and extension

---------------------------------------------------------------------

INSTALLATION (LOCAL DEVELOPMENT)

Prerequisites
- Node.js (LTS recommended)
- npm / yarn / pnpm

Install & Run

npm install
npm run dev

The application will run at:
http://localhost:5173

---------------------------------------------------------------------

SCRIPTS

npm run dev       Start development server
npm run build     Create production build
npm run preview   Preview production build locally

---------------------------------------------------------------------

DEPLOYMENT

Platform: Vercel

Build Command: npm run build
Output Directory: dist

Steps
1. Fork or clone the repository
2. Import the project into Vercel
3. Use default Vite settings
4. Deploy

---------------------------------------------------------------------

LICENSE

MIT License
Free to use, modify, and distribute.

---------------------------------------------------------------------

## 👨‍💻 AUTHOR

```text
🧑 Name      : Shitanshu Singh
💻 GitHub    : @silence91169
🎨 Project   : Och
🌐 Live Demo : https://och91169.vercel.app/
```
