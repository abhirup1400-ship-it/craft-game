# 🧱 OpenCraft · Animals & Biomes · Ultra Smooth

A fully browser-based 3D voxel building game inspired by Minecraft — built with Three.js. No installation, no backend, no save required. Play instantly in any modern browser.

**Made by Abhirup Payne**

---

## 🎮 Play Online

👉 **[Play on GitHub Pages](https://YOUR-USERNAME.github.io/opencraft-game/)**

> Replace `YOUR-USERNAME` with your actual GitHub username after deploying.

---

## ✨ Features

- 🌍 **Procedurally generated world** — Grass plains, desert biomes, forest clusters, underground caves
- 🐄 **Living animals** — Cows, chickens, pigs, and sheep wander the world with collision-aware movement
- 💧 **Water & swimming** — Placeable water with swim physics (Space to swim up)
- ☀️🌙 **Day / Night cycle** — Toggle between full day and night with stars and moonlight
- 🌧️❄️ **Weather system** — Rain and snow particle effects
- 🧱 **Block building & breaking** — 7 block types: Grass, Dirt, Stone, Wood, Gold, Sand, Water
- 👤 **3 character classes** — Explorer (balanced), Speedy (+40% speed), Jumper (+50% jump)
- ⚡ **Ultra smooth** — 60 FPS target with instanced rendering and optimized physics
- 📘 **In-game manual** — Slide-out controls reference panel

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `W A S D` | Move |
| `Space` | Jump / Swim up |
| `Mouse` | Look around |
| `Click` | Break or Create block |
| `Right Click` | (Disabled — use mode button) |
| `1 – 7` | Select block slot |
| `Enter` | Break / Create (keyboard) |

---

## 🧱 Blocks

| Slot | Block | Color |
|------|-------|-------|
| 1 | Grass | Green |
| 2 | Dirt | Brown |
| 3 | Stone | Grey |
| 4 | Wood | Light brown |
| 5 | Gold | Yellow (metallic) |
| 6 | Sand | Beige |
| 7 | Water | Blue (transparent) |

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Method 1 — Automatic (GitHub Actions) ✅ Recommended

1. **Create a new GitHub repository** (e.g. `opencraft-game`)
2. **Upload all project files** to the `main` branch
3. Go to **Settings → Pages**
4. Under **Source**, select **GitHub Actions**
5. Push to `main` — the workflow will auto-deploy
6. Your game will be live at `https://YOUR-USERNAME.github.io/opencraft-game/`

### Method 2 — Manual (GitHub Pages from branch)

1. Create a new repo and push all files to `main`
2. Go to **Settings → Pages**
3. Source: **Deploy from branch** → `main` → `/ (root)`
4. Save — GitHub will deploy in ~1 minute

---

## 📁 Project Structure

```
opencraft-game/
├── index.html              ← Main game (self-contained)
├── 404.html                ← GitHub Pages fallback redirect
├── README.md               ← This file
└── .github/
    └── workflows/
        └── deploy.yml      ← Auto-deploy to GitHub Pages
```

> The entire game runs from a single `index.html` — no npm, no build step, no server needed.

---

## 🛠️ Tech Stack

- **[Three.js r128](https://threejs.org/)** — 3D rendering via WebGL
- **PointerLockControls** — First-person camera
- **InstancedMesh** — High-performance block rendering
- **Pure vanilla JS** — No frameworks, no dependencies beyond Three.js

---

## ⚠️ Notes

- **No save system** — World resets on page reload (by design)
- Works best in **Chrome / Edge** (desktop)
- Requires a browser with **WebGL support**
- Pointer lock requires a user gesture (click to start)

---

## 📜 License

MIT License — free to use, modify, and share.

---

*OpenCraft · Animals & Biomes · Ultra Smooth — by Abhirup Payne*
