# Expertz Center — Enterprise IT & Infrastructure Website

Official high-performance enterprise portal for **Expertz Center (Pvt) Ltd.**
Featuring campus networking, hybrid cloud, cybersecurity SOC, and data center compute systems.

---

## 🚀 Quick Start Guide

### Prerequisites
- Node.js (version 18.x, 20.x, or 22.x recommended)
- npm (version 9.x or higher)

### 1. Installation
Clone or extract the repository, open a terminal in the project directory, and run:
```bash
npm install
```

### 2. Local Development Server
Start the local Vite development server:
```bash
npm run dev
```
The application will be accessible at: `http://localhost:3000` (or `http://localhost:5173`).

### 3. Production Build
Generate an optimized production distribution bundle:
```bash
npm run build
```
The compiled static assets will be output to the `dist/` directory.

### 4. Preview Production Build Locally
```bash
npm run preview
```

---

## 🌐 Deploying to Hosting Platforms

### A. Deploy to Vercel (Recommended)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project root.
3. Accept the default Vite configuration.

### B. Deploy to Netlify
1. Drag and drop the `dist` folder into Netlify Drop, or:
2. Connect your Git repository with build command: `npm run build` and publish directory: `dist`.

### C. Deploy to GitHub Pages / Custom Domain
1. In `vite.config.ts`, set `base: '/repo-name/'` if deploying to a subdirectory, or `base: '/'` for root/custom domain.
2. Push to GitHub and enable GitHub Actions static pages deployment.

---

## 🛠️ Technology Stack
- **Framework**: React 19 + TypeScript
- **Styling**: Tailwind CSS v4
- **Icons**: Lucide React
- **Animations & Transitions**: CSS transitions + Lucide
- **Exporting**: JSZip for offline client-side source bundling

---

## 🏢 Business Details
- **Company**: Expertz Center (Pvt) Ltd.
- **Headquarters**: Suite # 407, Ibrahim Trade Tower, Plot # 1, Block 7/8, MCHS, Shahrah-e-Faisal, Karachi, Pakistan
- **Phone**: +92-21-34554747
- **Email**: support@expertzcenter.com
- **Website**: https://expertzcenter.com
