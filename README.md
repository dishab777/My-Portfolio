# ⚡️ Personal Brand Portfolio | Disha Bothra

A high-performance, accessibility-first personal portfolio website designed to showcase my journey as a **Creative Technologist** and **B.Tech CSE Student**. 

Built with **Semantic HTML5**, **CSS3 (Variables & Animations)**, and **Vanilla JavaScript**, this project focuses on performance, inclusivity, and a modern aesthetic.

## 🚀 Live Demo
**[View the Live Site Here](https://dishab777.github.io/My-Portfolio/)**

---

## ✨ Key Features

* **🎨 Dynamic Theme Engine:** Robust Light/Dark mode toggle that persists user preference via `localStorage`.
* **♿ Accessibility (A11y) First:**
    * Semantic HTML landmarks (`<nav>`, `<main>`, `<article>`) for screen readers.
    * "Skip to Main Content" link for keyboard navigation.
    * High contrast ratios meeting WCAG AA standards.
    * `prefers-reduced-motion` support.
* **⚡️ High Performance:**
    * Zero dependencies/frameworks (Pure Vanilla JS).
    * Lazy loading for images.
    * Optimized CSS animations (`transform` & `opacity`).
* **📂 Filterable Project Gallery:** A JavaScript-powered filtering system to sort projects by tech stack (JS, CSS, Design) with ARIA live region support.
* **⏳ Experience Timeline:** A structured, vertical timeline view for professional experience and education.
* **🏆 Verification Ready:** Direct links to verify certifications (IBM, Google, Microsoft) with credential IDs.

---

## 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Core** | HTML5, CSS3, JavaScript (ES6+) |
| **Styling** | CSS Variables (Custom Properties), Flexbox, CSS Grid |
| **Icons** | Font Awesome 6 |
| **Fonts** | System Fonts stack (for max performance) |
| **Animation** | CSS Keyframes, Intersection Observer API |

---

## 📂 Project Structure

```bash
portfolio/
├── index.html          # Main HTML structure (Semantic & Accessible)
├── style.css           # Global styles, variables, and dark mode logic
├── script.js           # Logic for filtering, theme toggle, and scroll animations
├── images/             # Folder for certificates and project screenshots
│   ├── Velocity.Blue.png
│   ├── IBM-Cert.jpg
│   └── ...
└── README.md           # Documentation
