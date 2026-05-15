<div align="center">

# 🚀 Gautam Pulakala — Portfolio

A modern, responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript.  
Featuring glassmorphism design, smooth animations, and a premium dark theme.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## 📸 Preview

| Hero Section | Skills Section |
|:---:|:---:|
| Gradient animated name with typewriter effect & code window card | 8 skill cards with colored icons and hover glow effects |

| Projects Section | Contact Section |
|:---:|:---:|
| Coming soon — project cards with hover overlays | Glassmorphism contact form with social links |

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎨 **Glassmorphism UI** | Semi-transparent cards with blur backdrop across all sections |
| 🌌 **Particle Canvas** | Animated interconnected particle network background |
| ⌨️ **Typewriter Effect** | Rotating text: *First-Year CSE Student*, *Aspiring Developer*, etc. |
| 📊 **Animated Counters** | Stats that count up when scrolled into view |
| 🃏 **3D Tilt Effect** | Cards tilt toward the mouse cursor on hover |
| 🎯 **Scroll Reveal** | Elements fade in and slide up as you scroll |
| 🌈 **Gradient Orbs** | Floating, blurred gradient spheres for ambient depth |
| 📱 **Fully Responsive** | Mobile hamburger menu, stacked layouts, adapted spacing |
| 🔗 **Social Links** | GitHub, LinkedIn, LeetCode |
| 📬 **Contact Form** | Animated submit button with success feedback |

---

## 🛠️ Tech Stack

This portfolio is built with **zero frameworks** — just clean, hand-crafted code:

```
📁 portfolio/
├── index.html      → Structure & content
├── style.css       → Styling, animations, responsive design
├── script.js       → Interactivity & effects
└── README.md       → You are here
```

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure, SEO meta tags |
| **CSS3** | Custom properties, glassmorphism, keyframe animations, grid/flexbox |
| **JavaScript** | Canvas API (particles), Intersection Observer (scroll reveals), DOM manipulation |
| **Google Fonts** | Inter (body) + JetBrains Mono (code) |
| **Font Awesome 6** | Icons for skills, social links, and UI elements |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/GAUTAM11019/portfolio.git
cd portfolio
```

### 2. Open in browser

Simply open `index.html` in any modern browser:

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

Or use a local server for the best experience:

```bash
# Python
python -m http.server 8080

# Then visit http://localhost:8080
```

> **No build step, no dependencies, no `npm install`.** It just works.

---

## 📂 Project Structure

```
index.html
├── Navigation ─────── Fixed navbar with smooth scroll & hamburger menu
├── Hero Section ───── Animated name, typewriter, code window, stats
├── About Section ──── Bio, info cards, experience timeline
├── Skills Section ─── 8 skill cards (C, Python, HTML, CSS, JS, Git, Java, C++)
├── Projects Section ── Coming soon placeholder
├── Contact Section ── Form, email, location, social links
└── Footer ─────────── Logo, copyright, social icons

style.css
├── Reset & Variables ─ Custom properties, color palette, fonts
├── Glass Card System ─ Reusable glassmorphism component
├── Section Styles ──── Per-section layout and typography
├── Animations ──────── Keyframes for orbs, particles, floating, pulse
├── Reveal System ───── Scroll-triggered fade-in transitions
└── Responsive ──────── 768px and 480px breakpoints

script.js
├── Particle Canvas ─── Animated particles with connection lines
├── Typewriter ──────── Rotating text with type/delete cycle
├── Navbar ─────────── Scroll effect, active link tracking, hamburger
├── Scroll Reveal ──── IntersectionObserver-based animations
├── Counter Animation ─ Stat numbers count up on scroll
├── Contact Form ───── Animated submit button simulation
└── Tilt Effect ─────── 3D perspective tilt on card hover
```

---

## 🎨 Customization

### Change colors

Edit the CSS custom properties in `style.css`:

```css
:root {
    --accent-1: #6366f1;       /* Primary accent */
    --accent-2: #8b5cf6;       /* Secondary accent */
    --accent-3: #a78bfa;       /* Light accent */
    --bg-primary: #0a0a0f;     /* Background */
}
```

### Update personal info

All personal content is in `index.html` — update your:
- Name, university, and bio text
- Social media URLs (GitHub, LinkedIn, etc.)
- Email address
- Skills and project cards

### Add real projects

Replace the "Coming Soon" placeholder in the Projects section with actual project cards. Each card supports:
- Project image/icon
- Technology tags
- Title & description
- Links to live demo and source code

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `> 768px` | Full desktop — 2-column hero, 3-column skills grid |
| `≤ 768px` | Tablet/mobile — single column, hamburger nav, 2-column skills |
| `≤ 480px` | Small mobile — stacked stats, full-width buttons |

---

[![Live Demo](https://img.shields.io/badge/Live-Demo-6366f1?style=for-the-badge&logo=vercel&logoColor=white)](https://gautampulakala.vercel.app/)


## 📄 License

This project is open source

---

<div align="center">

**Built with ❤️ by Gautam Pulakala**

*First-year B.Tech CSE @ MIT Manipal*

[![GitHub](https://img.shields.io/badge/GitHub-GAUTAM11019-181717?style=flat-square&logo=github)](https://github.com/GAUTAM11019)

</div>
