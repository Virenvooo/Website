# Vir's Personal Website

A clean, cosmic-themed personal website with purple/neon vibes, floating particles, click effects, anime mascot, Discord & Spotify widgets, and a dedicated projects showcase page.

Live at: https://virenvooo.github.io/website/  
(← replace with your actual GitHub Pages / custom domain link when you deploy it)

![Website preview](https://i.imgur.com/ZFulVl8.png)  

## ✨ Features

- Dark cosmic purple aesthetic with floating blurred orbs
- Interactive particles.js background
- Click → colorful particle burst effect
- Floating anime-style mascot (desktop only)
- Glassmorphism cards + hover lift effects
- Responsive design (mobile → tablet → desktop)
- Discord status widget
- Spotify "Currently Playing" embed
- Dedicated `/projects` page with card grid & hover expand icons
- Simple, lightweight, no heavy frameworks

## 🛠️ Tech Stack

- HTML5 + CSS3 (vanilla with custom properties)
- Google Fonts (Poppins)
- particles.js (background particles)
- Custom click-canvas effect (very lightweight)
- External widgets: Discord banner, Spotify GitHub profile card
- Lucide icons (optional – for project buttons)

## 📂 Project Structure
website/
├── index.html              # main landing page
├── styles.css              # global styles + theme
├── projects_page/
│   ├── projects.html       # projects showcase
│   └── projects.css        # project-specific styles
├── oneko.js                # optional fun cat cursor (if you kept it)
└── README.md

## 🚀 How to run locally

1. Clone the repository

```bash
git clone https://github.com/Virenvooo/website.git
cd website
Open index.html in your browser
You can use any local server if you prefer (recommended):
Bash# with Python (most people have it)
python -m http.server 8000
# or
npx serve
# or VS Code Live Server extension
Then visit http://localhost:8000
```

🌌 Customization
Quick places to change things:

Colors → edit :root variables in styles.css
Avatar / mascot → replace img src in index.html
Particles config → look at the <script> block at bottom of index.html
Projects → add/remove cards in projects_page/projects.html
Widgets → update user IDs in the img src URLs

📜 License
MIT License – feel free to fork, modify, use as inspiration or even as a template.
Made with ♥ by a 14-year-old who likes animanga, tech & purple colors
Last updated: February 2026
