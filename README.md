# Fazlur Rahman — Data Analyst & ML Engineer Portfolio

![Portfolio Preview](public/assets/images/projects/pipeline.webp)

A modern, high-performance interactive portfolio built with React 19, Vite, and Tailwind CSS v4. This application showcases professional projects, academic work, and personal interests through a cinematic, technical lens.

---

## Key Features

- **Project Intelligence**: Metadata-driven gallery with 13+ detailed case studies featuring custom interactive dashboards (IoT, ML, E-commerce, etc.).
- **Global Travel Log**: Animated, physics-based world map visualizing international travel history, linked to a chronological travelogue with high-resolution imagery.
- **Terminal UI Component**: A custom, animated "Outside the Terminal" section in Interests, mimicking a macOS terminal with staggered text reveal and a blinking cursor.
- **Digital Library**: Filterable, categorized showcase of professional and personal reading materials.
- **Performance First**: Zero-runtime CSS with Tailwind v4, word-by-word scatter animations with Framer Motion, and optimized WebP asset management.
- **Automated Asset Pipeline**: Integrated image optimization loop using Sharp to normalize and convert assets.

---

## Design System

- **Typography**: Primary typeface is **Geist** (by Vercel), chosen for its exceptional legibility and modern technical aesthetic.
- **Monospace**: **JetBrains Mono** for code fragments and terminal-inspired UI blocks.
- **Theme**: A custom-curated **Dark Navy/Slate** palette (`#0a1118`) with glowing primary cyan accents (`#11b4d4`).
- **Motion**: Physics-based transitions and entrance animations powered by **Framer Motion**.

---

## Technical Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## Getting Started

### 1. Installation
```bash
git clone https://github.com/Montasir00/Portfolio-Website.git
cd Portfolio-Website
npm install
```

### 2. Development
```bash
npm run dev
```
Runs the app in development mode at `http://localhost:3000/Portfolio-Website/`.

### 3. Optimization
To convert new assets to optimized WebP and resize them:
```bash
npm run optimize
```

### 4. Build & Deployment
```bash
npm run build
npm run deploy
```

---

## Site Architecture

![Site Architecture](public/assets/images/architecture.png)

The application follows a modular architecture designed for scalability and maintainability. The central `App.tsx` router orchestrates the flow between high-level components and their specialized sub-pages.

---

## Directory Structure

- `/src/components/` — UI components (Terminal, Map, Dashboards, Page Views).
- `/src/constants/` — Centralized data for projects, experience, travel, and books.
- `/scripts/` — Node.js automation scripts (Image processing, metadata fetching).
- `/public/assets/` — Optimized production assets (WebP images, PDF Resume).

---

## Contact

**Fazlur Rahman**
- **Email**: [fazlurrahaman365@gmail.com](mailto:fazlurrahaman365@gmail.com)
- **GitHub**: [@Montasir00](https://github.com/Montasir00)
- **Location**: Messina, Italy (University of Messina)
