# Elian Kent – Portfolio

A modern, high-fidelity portfolio website extracted from Framer with 100% visual and interactive spring-motion fidelity, rebuilt as a Next.js 14 App Router application alongside a standalone static HTML export.

**Designed & Developed by [Hazem Elerefy](https://github.com/hazemelerefey)**

---

## Architecture & Project Structure

- **Next.js App Router (`app/`)**: Production Next.js 14 application serving the exact compiled DOM and Framer Motion client runtime scripts with zero compromises.
- **Standalone Static Export (`framer-export/static-site/`)**: A completely self-contained static site that runs on any static web server or CDN with zero external build dependencies.
- **Media & Assets (`public/images/`)**: All high-resolution responsive images and vectors saved locally.
- **CMS Data (`data/`)**: Structured JSON exports for all Works (`works.json`) and Blog articles (`blogs.json`).

---

## Routes Included

- `/` – Home / Hero & Featured Works
- `/works` – Projects Overview
- `/works/destello` – Case Study: Destello
- `/works/zayla` – Case Study: Zayla
- `/works/veon` – Case Study: Veon
- `/works/glidex` – Case Study: Glidex
- `/works/sienna` – Case Study: Sienna
- `/blogs` – Articles & Thoughts
- `/blogs/why-framer-development-is-modern-creation`
- `/blogs/the-roadmap-behind-great-design`
- `/blogs/designing-a-brand-that-speaks-without-words`
- `/blogs/building-brand-atmosphere-through-color-typography`
- `/blogs/from-design-to-fully-functional-websites`
- `/blogs/how-visual-hierarchy-shapes-user-decisions`
- `/blogs/why-framer-makes-the-workflow-effortless`
- `/blogs/designing-with-intent-why-clarity-beats-complexity`
- `/404` – Custom 404 Error Page

---

## Watermarks & Attribution Standards

- **0 Watermarks**: All Framer badges, "Made in Framer" labels, tooltips, and telemetry tags have been 100% excised.
- **Attribution**: Signature strictly embedded in the footer and `<head>` metadata (`author`, `creator`, `designer`), preserving the clean aesthetic of the main canvas.

---

## Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Start production server
npm run start
```
