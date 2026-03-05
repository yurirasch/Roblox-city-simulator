# 🏙️ Roblox City Simulator

A **3D browser-based city simulator** inspired by Roblox's blocky style, built with [Three.js](https://threejs.org/). Open it directly in your browser — no installation required.

## 🌐 Live Demo

**👉 [https://yurirasch.github.io/Roblox-city-simulator/](https://yurirasch.github.io/Roblox-city-simulator/)**

![Roblox City Simulator Screenshot](https://github.com/user-attachments/assets/354d4f08-0d6e-4828-bcd9-a74c0ed30eba)

## ✨ Features

- **Procedurally generated city** — 12×12 block grid with colourful buildings, roads, sidewalks, parks and trees
- **Orbit camera** — rotate, pan and zoom with mouse or touch (pinch)
- **Animated traffic** — 40 cars driving along road lanes
- **Day / Night toggle** — ambient lighting changes, windows glow at night, star field appears
- **New City** — regenerate an entirely new layout with one click
- **Live stats** — building and car count shown on screen

## 🎮 Controls

| Input | Action |
|---|---|
| Left drag | Rotate camera |
| Right drag | Pan |
| Scroll wheel | Zoom in / out |
| Pinch (touch) | Zoom in / out |
| ☀️ Day / 🌙 Night button | Toggle lighting |
| 🚗 Toggle Cars button | Show / hide traffic |
| 🔄 New City button | Regenerate city |

## 🚀 Run Locally

```bash
# Any static file server works, e.g.:
npx serve .
# or
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

> **No build step required.** All dependencies (Three.js r158) are bundled in the `lib/` folder.
