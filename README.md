# Shantanu Kundu — Portfolio

A modern, responsive personal portfolio website built with **HTML, CSS, and JavaScript**.  
Features a sleek glassmorphism UI, animated hero section, scroll-reveal effects, theme toggle (dark/light), contact form integration, and **auto-loaded projects from GitHub** with a smart fallback + caching system.

🌐 **Live Demo:** https://shantanukunduportfolio.netlify.app/

## ✨ Features
- ✅ Modern UI (glassmorphism + gradient blobs + subtle noise)
- ✅ Fully responsive (mobile nav + optimized layout)
- ✅ Dark/Light theme toggle (saved in LocalStorage)
- ✅ Scroll reveal animations + scroll spy active nav
- ✅ “Back to top” smooth scroll
- ✅ Contact form via **Formspree**
- ✅ Projects section auto-fetches latest updated repos from **GitHub API**
  - Cache (24h) to reduce API calls
  - Fallback projects shown if GitHub API fails (rate limit / network issue)

## 🧰 Tech Stack
- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **Font Awesome** (icons)
- **Google Fonts (Inter)**
- **Formspree** (contact form)
- **GitHub REST API** (project auto-load)

## 📁 Project Structure
```txt
.
├── index.html
├── styles.css
├── script.js
└── assets/
    ├── favicon.png
    ├── profile.png
    └── ShantanuKundu-CV.pdf
