# DSRT.js – Next-Gen 3D Web Engine

![Build](https://img.shields.io/github/actions/workflow/status/projectmydsrt-bro/dsrt-nextjs/ci.yml?branch=main?color=green)
![Version](https://img.shields.io/github/package-json/v/projectmydsrt-bro/dsrt-nextjs?color=blue)
![License](https://img.shields.io/github/license/projectmydsrt-bro/dsrt-nextjs?color=green)
![Stars](https://img.shields.io/github/stars/projectmydsrt-bro/dsrt-nextjs?style=social)
![Forks](https://img.shields.io/github/forks/projectmydsrt-bro/dsrt-nextjs?style=social)
![Open Issues](https://img.shields.io/github/issues/projectmydsrt-bro/dsrt-nextjs)
![Next.js](https://img.shields.io/badge/Next.js-14-blue?logo=next.js)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow?logo=javascript)


---

## 🔹 About DSRT.js

**DSRT.js** is a **Next-Gen 3D Web Engine** designed as a modern, upgraded alternative to Three.js.  
It provides **fullscreen interactive 3D backgrounds, advanced geometry, lighting, and post-processing effects** for web apps, demos, and landing pages.  

This project includes a **Next.js landing page** showcasing DSRT.js, interactive demos, and collaboration tools.

---

## 🚀 Features

- Fullscreen interactive 3D hero canvas  
- Modern, upgraded geometry & mesh system  
- Advanced lighting: directional, point, ambient, spot  
- Post-processing effects: Bloom, Fog, Neon, Metallic  
- Error handling & recovery via `DSRT.onError()`  
- Responsive layout compatible with all screen sizes  
- Next.js integration with reusable components  
- Collab CTA, showcase section, and GitHub integration  
- Documentation & examples included  

---

## 💻 Installation

```bash
# Clone the repo
git clone https://github.com/projectmydsrt-bro/dsrt-nextjs.git
cd dsrt-nextjs

# Install dependencies
npm install
# or
yarn install

# Run development server
npm run dev
# or
yarn dev

Open http://localhost:3000 to view the landing page.


---

📖 Usage

DSRT.js can be used in your own pages or components:

// Import DSRT.js from public folder
import DSRT from '../public/dsrt.js';

DSRT.init({
  container: document.getElementById('canvas-container'),
  background: 'nebula',
  debug: true,
});

DSRT.addMesh({ type: 'torus', size: 2, color: '#00ffff' });
DSRT.addLight({ type: 'point', intensity: 1.5, position: [5, 5, 5] });
DSRT.animateMesh('torus', { rotationY: 0.01 });


---

📚 Documentation & Examples

API Reference

Usage Guide

Roadmap

FAQ

Interactive demos included in /examples



---

🤝 Collaboration

We welcome contributions!

Fork the repo and create a branch

Follow the Contributing Guidelines

Report security issues via SECURITY.md

Follow Code of Conduct

Star & fork the project if you like it!


Join the project on GitHub:



---

⚖️ License

This project is licensed under the MIT License – see LICENSE for details.
All third-party libraries and assets are listed in NOTICE.md.


---

📝 Changelog

See CHANGELOG.md for full release notes and history.


---

🎉 Credits

Original inspiration: Three.js (upgraded & modernized)

Tailwind CSS for styling

Contributors: See GitHub contributors
