# 🌙 Lunara — Romantic MoonVerse

> **An Ethereal 3D Ocean of Love & Celestial WebGL Experience**

[![Three.js](https://img.shields.io/badge/Three.js-r160-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![WebGL](https://img.shields.io/badge/WebGL-2.0-blue?style=for-the-badge&logo=webgl)](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)
[![License](https://img.shields.io/badge/License-ISC-green.svg?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](https://github.com/saklincodes/Lunara/pulls)

**Lunara** (Romantic MoonVerse) is an immersive, interactive 3D WebGL web application that brings a serene, romantic ocean under a glowing celestial moon to life. Built using **Three.js**, custom GLSL shaders, and post-processing bloom effects, Lunara offers a multi-sensory journey through procedural celestial realms, drifting wish lanterns, meteor showers, and floating rose petal storms.

---

## ✨ Key Features

- 🌊 **Realistic 3D Ocean Shader**: Dynamic water rendering with normal-mapped ripple animations and realistic moonlight reflections.
- 🌌 **6 Procedural Celestial Realms**:
  - **The Giant Moonlit Horizon** — Deep ocean solitude beneath a radiant lunar glow.
  - **Drifting Wish Lanterns** — Warm amber lanterns softly ascending into the night sky.
  - **Celestial Aurora Borealis Curtain** — Ethereal green & teal atmospheric curtains waving across the sky.
  - **Cosmic Rose Petal Storm** — Crimson & pink petals dancing gracefully over glowing waves.
  - **Blazing Meteor Starfall** — High-speed shooting stars trailing light across the cosmos.
  - **Twilight Violet & Milky Way** — Deep violet sky bathed in celestial starlight.
- 📜 **Interactive Constellation Poetry**: Glassmorphic UI displaying poetic verses synced with smooth atmospheric realm transitions.
- ✨ **Stardust Canvas Trails**: Interactive 2D particle canvas that follows cursor and touch movements with glowing stardust.
- 🌸 **Particle Engines**: Custom geometry particle systems for floating rose petals, glowing wish lanterns, and meteor streaks.
- 💫 **Unreal Bloom Post-Processing**: High-dynamic-range lens bloom using Three.js `EffectComposer` & `UnrealBloomPass`.
- 📱 **Fully Responsive**: Optimized for desktop, tablet, and mobile browsers with fluid 60 FPS animation loops.

---

## 🛠️ Tech Stack & Architecture

| Technology | Description |
| :--- | :--- |
| **Three.js (r160)** | 3D Scene graph, perspective camera, lights, and mesh geometries |
| **Custom Shaders** | Water normal mapping, custom star shaders, and procedural aurora meshes |
| **Post-Processing** | `EffectComposer`, `RenderPass`, `UnrealBloomPass` |
| **HTML5 & CSS3** | Modern Glassmorphic card overlay, keyframe animations, Google Fonts |
| **JavaScript (ES6+)** | Modular script execution with `importmap` |

---

## 📂 Project Structure

```text
Lunara/
├── index.html       # Main application (HTML structure, Glassmorphic CSS, 3D WebGL Engine)
├── package.json     # Node.json configuration & serve scripts
└── README.md        # Documentation
```

---

## 🚀 Quick Start & Local Setup

No complex build pipeline required! You can run Lunara directly in any browser.

### Option 1: Using Node.js / `npm` (Recommended)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/saklincodes/Lunara.git
   cd Lunara
   ```

2. **Start the local server**:
   ```bash
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:3000`.

### Option 2: Static File Host / Live Server

Simply host `index.html` using any HTTP server (e.g., VS Code Live Server, Python `http.server`, or static hosting like Vercel / GitHub Pages).

---

## 🎮 How to Experience Lunara

- **Click / Tap Poetry Card**: Transitions the environment seamlessly into the next celestial realm.
- **Drag & Pan**: Orbit camera around the 3D ocean and lunar horizon.
- **Move Cursor / Touch**: Creates a glowing trail of stardust across the screen.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check the [Issues Page](https://github.com/saklincodes/Lunara/issues).

---

## 📄 License

This project is licensed under the **ISC License**.

---

<p align="center">
  Crafted with ❤️ by <a href="https://github.com/saklincodes"><strong>Saklin</strong></a>
</p>
