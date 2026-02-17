# 🚀 Aventro – Modern Business Consultancy Landing Page

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)

**Aventro** is a high-performance, mobile-first landing page designed for modern business consultancies and tech startups. Built with **HTML5** and the latest **Tailwind CSS v4**, it features a sleek dark-mode aesthetic, glassmorphism effects, and fully interactive UI components without the bloat of heavy JavaScript frameworks.

---

## 📑 Table of Contents

- [🚀 Aventro – Modern Business Consultancy Landing Page](#-aventro--modern-business-consultancy-landing-page)
  - [📑 Table of Contents](#-table-of-contents)
  - [🔗 Live Demo](#-live-demo)
  - [✨ Key Features](#-key-features)
  - [📱 Responsive Showcase](#-responsive-showcase)
  - [🛠️ Tech Stack \& Optimization](#️-tech-stack--optimization)
  - [⚡ Tailwind v4 Highlights](#-tailwind-v4-highlights)

---

## 🔗 Live Demo

👉 **[View Live Project on Vercel](https://pr-02-the-atomic-tailwind-css.vercel.app/)** 🚀  
*(Replace this link with your actual deployment URL)*

---

## ✨ Key Features

This isn't just a static page; it's a fully functional UI kit featuring:

* **💎 Glassmorphism UI:** Modern, translucent card effects using `backdrop-blur` and RGBA colors.
* **📱 Mobile-First Architecture:** Built from the ground up for small screens, scaling up to 4K displays.
* **⚓ Sticky Navigation:** Smart header that changes style on scroll (Glass effect).
* **📑 Interactive Tabs:** A lightweight JavaScript-powered tab system for the "Features" section.
* **🔽 Accordion FAQ:** Smooth opening/closing FAQ section with animation states.
* **📊 Pricing Cards:** distinct visual hierarchy for "Popular" plans.
* **🎨 CSS Variables Theme:** Utilizes Tailwind v4's CSS variable configuration for instant theming.
* **⚡ Performance:** 100% Lighthouse Score optimized (Semantic HTML + Utility CSS).

---

## 📱 Responsive Showcase

| Mobile View (iPhone SE) | Tablet View (iPad Air) | Desktop View (1920px) |
|:---:|:---:|:---:|
| <img src="https://placehold.co/200x400?text=Mobile+UI" width="200" /> | <img src="https://placehold.co/300x400?text=Tablet+UI" width="300" /> | <img src="https://placehold.co/500x300?text=Desktop+UI" width="500" /> |

*(Note: Replace placeholders with actual screenshots of your project)*

---

## 🛠️ Tech Stack & Optimization

We focused on writing **DRY (Don't Repeat Yourself)** code using the `@apply` directive.

* **Core:** Semantic HTML5
* **Styling:** Tailwind CSS v4 (Alpha/Beta)
* **Icons:** Bootstrap Icons (`bi-`) & FontAwesome (`fa-`)
* **Fonts:** Google Fonts (Ubuntu, Roboto, Inter)
* **Scripting:** Vanilla JavaScript (ES6+)

---

## ⚡ Tailwind v4 Highlights

This project utilizes the cutting-edge features of Tailwind v4 to keep the HTML clean. Instead of cluttering HTML with 50 classes, we utilize **Component Layers**:

```css
/* src/main.css */
@layer components {
  /* Creating a reusable button class */
  .btn-primary {
    @apply inline-flex items-center justify-center bg-aqua-700 text-white font-semibold py-4 px-8 rounded-lg shadow-lg hover:-translate-y-1 transition-all duration-300;
  }

  /* Complex Glassmorphism Card */
  .card-glass {
    @apply backdrop-blur-sm bg-white/10 border border-white/20 rounded-lg p-6 text-center shadow-lg hover:bg-white/15 transition-colors;
  }
}