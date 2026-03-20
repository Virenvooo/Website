# Vir's Personal Website
A clean, crimson-themed personal website inspired by Ayanokoji Kiyotaka, with falling playing cards, red neon vibes, floating particles, click effects, anime mascot, Discord & Spotify widgets, and a dedicated projects showcase page.

**Live demo:** https://virenvo.pages.dev/

![Website preview](https://i.imgur.com/3PIE58L.jpeg)

## ✨ Features
- Deep crimson aesthetic with floating blurred orbs — inspired by Ayanokoji Kiyotaka (COTE)
- Falling playing cards background (♠♥♦♣) — lightweight canvas, throttled to 30fps
- Custom ♠ red cursor
- Click → red particle burst effect
- Mouse spotlight that follows the cursor
- Random Ayanokoji quote on every page load
- Auto-calculated age badge (updates every Oct 13)
- Tooltip on every social link
- Slide-up entrance animation on the main card
- Floating anime-style mascot (visible on desktop)
- Fully responsive (mobile → tablet → desktop)
- Discord status widget
- Spotify "Currently Playing" embed
- Dedicated `/projects` page with card grid, hover expand icons & staggered entrance animation
- Locked "Coming Soon" cards for upcoming projects
- Lightweight – no heavy frameworks

## 🛠 Tech Stack
- HTML5 + CSS3 (vanilla with CSS custom properties)
- Google Fonts (Poppins)
- particles.js (background particles)
- Custom lightweight canvas — falling cards & click effect
- External widgets: Discord banner, Spotify GitHub profile card

## 📂 Folder Structure
```
website/
├── index.html              # Main landing page
├── styles.css              # Global styles & theme
├── projects_page/
│   ├── projects.html       # Projects showcase page
│   ├── projects.css        # Project-specific styles
│   ├── oneko.js
│   └── oneko.gif
├── oneko.gif
├── oneko.js
└── README.md
```

## 🚀 How to Run Locally
1. Clone the repository
```bash
git clone https://github.com/Virenvooo/website.git
cd website
```
2. Open the site by opening `index.html` in your browser

## 📜 License
MIT License — feel free to fork, modify, use as inspiration, or take parts for your own site.

Made with ♥ by Vir. Last updated: March 2026
