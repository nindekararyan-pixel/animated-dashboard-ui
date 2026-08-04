# animated-dashboard-ui
A fully animated analytics dashboard UI built with pure HTML & CSS — glassmorphism cards, animated charts, and a CSS-only count-up, no JavaScript.

# Pulse — Animated Analytics Dashboard UI

A stunning, fully animated analytics dashboard built with **pure HTML & CSS** — no JavaScript, no frameworks, no build tools. Just open the file and it runs.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![No JS](https://img.shields.io/badge/JavaScript-none-critical)

## Preview

> Add a screenshot or GIF of the dashboard here once you have one.
>
> `![Dashboard Preview](preview.png)`

## Features

- 🎨 **Glassmorphism UI** — frosted-glass cards, soft borders, ambient blurred background glow
- 📊 **Animated line chart** — SVG path that "draws" itself in on load, with gradient area fill
- 🍩 **Animated donut chart** — CSS `conic-gradient` ring that sweeps in using animated custom properties
- 📈 **Animated bar chart** — bars grow in with staggered timing
- 🌡️ **Animated gauge** — half-circle progress meter for goal tracking
- 🔢 **CSS-only count-up numbers** — stat cards roll up from 0 using `@property` and CSS counters (no JS!)
- ✨ **Micro-interactions** — hover lift/glow on cards, staggered entrance animations, active nav states
- ♿ **Accessible** — respects `prefers-reduced-motion`, responsive down to mobile
- 📱 **Fully responsive** — sidebar collapses and grid reflows on smaller screens

## Tech Stack

- **HTML5** — semantic structure, inline SVG for charts and icons
- **CSS3** — Grid & Flexbox layout, `conic-gradient`, `@property` for animated custom properties, keyframe animations
- **Fonts** — [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

No external CSS/JS libraries. Everything is hand-built in a single file.

## Getting Started

No installation or build step required.

1. Clone the repo:
   ```bash
   git clone  https://github.com/nindekararyan-pixel/pulse-dashboard.git
   ```
2. Open `dashboard.html` directly in your browser.

That's it — it's a static file.

## Browser Support

Built and tested primarily for **Chrome / Edge** (Chromium-based browsers), since the count-up number animation relies on `@property`, a newer CSS feature. On browsers without support, the numbers simply display their final value instead of animating — everything else (charts, layout, hover effects) works everywhere modern CSS Grid/Flexbox is supported.

## Folder Structure

```
pulse-dashboard/
├── dashboard.html   # Single-file dashboard (HTML + CSS)
├── README.md
└── .gitignore
```

## License

Free to use for learning, portfolio, or personal projects.

## Author

Built by **Aryan** — self-taught developer focused on pure CSS/HTML craftsmanship.