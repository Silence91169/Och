🎨 Och — Modern Animated Landing Page

Status: Live · Responsive · Animated
Frontend: React · Vite · Tailwind CSS
Animations: Framer Motion / Smooth Scroll
Deployment: Vercel
License: MIT (recommended)

Och is a modern, animated landing page / portfolio-style website designed to deliver a smooth, visually engaging user experience. Built with a component-driven architecture and enhanced with scroll-based animations, Och focuses on clean UI, performance, and responsiveness across all devices.

Whether used as a personal portfolio, startup landing page, or design showcase, Och provides a strong foundation with reusable components and motion-first interactions.

📚 Table of Contents

🎨 Och — Modern Animated Landing Page

📌 Live Demo

📁 Project Structure

🛠 Tech Stack

🧩 High-Level Architecture

🚀 Features

⚙️ Installation (Local Development)

🧪 Usage Guide

🚀 Deployment

🗺️ Roadmap

🤝 Contributing

📝 License

👨‍💻 Author

📌 Live Demo
Platform	Link
Web	https://och-eta.vercel.app/
📁 Project Structure
och/
├─ public/                    # Static assets
├─ src/
│  ├─ assets/                 # Images, icons, fonts
│  ├─ components/             # Reusable UI components
│  │  ├─ Navbar.jsx
│  │  ├─ Hero.jsx
│  │  ├─ About.jsx
│  │  ├─ Projects.jsx
│  │  ├─ Footer.jsx
│  │  └─ Button.jsx
│  ├─ styles/                 # Global & custom styles
│  ├─ App.jsx                 # Root component
│  ├─ main.jsx                # React entry point
│  └─ index.css               # Tailwind CSS imports
├─ package.json
├─ vite.config.js
└─ README.md

🛠 Tech Stack
Languages & Frameworks

Frontend: React (JavaScript, ES Modules)

Build Tool: Vite

Styling: Tailwind CSS

Libraries & Tools

Animations: Framer Motion (optional)

Smooth Scrolling: Locomotive Scroll / Lenis (optional)

Icons: Lucide / React Icons

Deployment: Vercel

Version Control: Git & GitHub

🧩 High-Level Architecture
┌─────────────────────────┐
│   React + Vite          │
│   (Component-Based UI)  │
│                         │
│   Tailwind CSS          │
│   Framer Motion         │
│   Smooth Scroll         │
└───────────┬─────────────┘
            │
            ▼
┌─────────────────────────┐
│   Static Build (dist)   │
│   Optimized Assets      │
└───────────┬─────────────┘
            │
            ▼
┌─────────────────────────┐
│   Vercel Deployment     │
│   Global CDN            │
└─────────────────────────┘


Key Architecture Notes

Fully client-side rendered

Component-driven layout

Animation-first UI design

Optimized production builds via Vite

CDN-backed deployment for fast loading

🚀 Features
UI & Design

Modern landing page layout

Clean typography and spacing

Minimalistic, professional design

Gradient accents and smooth transitions

Animations & Interactions

Scroll-based motion effects

Section reveal animations

Smooth page transitions

Micro-interactions for buttons and links

Performance & Responsiveness

Mobile-first responsive design

Optimized assets and builds

Fast load times with Vite

Cross-browser compatibility

Developer Experience

Reusable component structure

Clean and readable codebase

Easy customization

Scalable project layout

⚙️ Installation (Local Development)
Prerequisites

Node.js (LTS recommended)

npm / yarn / pnpm

1) Clone the Repository
git clone https://github.com/your-username/och.git
cd och

2) Install Dependencies
npm install

3) Start Development Server
npm run dev


Open the URL shown in the terminal (usually):

http://localhost:5173

🧪 Usage Guide
Available Scripts
npm run dev      # Start development server
npm run build    # Create production build
npm run preview  # Preview production build locally

Customization Tips

Update content inside components/

Replace images in assets/

Modify theme colors via tailwind.config.js

Add or remove animation logic via Framer Motion

🚀 Deployment

This project is deployed on Vercel.

Deploy Your Own Version

Fork or clone the repository

Import the project into Vercel

Use default Vite settings:

Build Command: npm run build
Output Directory: dist


Deploy 🚀

🗺️ Roadmap
Planned Enhancements

Dark mode toggle

CMS-based content support

Page transition loader

SEO & Open Graph optimization

Accessibility improvements (ARIA)

🤝 Contributing

Contributions are welcome!

# Steps
Fork the repo
Create a feature branch
git checkout -b feature/new-feature
Commit changes
git commit -m "Add new feature"
Push to GitHub
Open a Pull Request

📝 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it.

👨‍💻 Author

Shitanshu Singh

GitHub: @silence91169

Project: Och

Live Demo: https://och-eta.vercel.app/
