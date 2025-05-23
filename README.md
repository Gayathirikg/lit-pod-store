# 🛍️ Customizable POD T-Shirt Store (Frontend Assessment)

This is a **Single Page Application (SPA)** built using **Lit Web Components**, demonstrating a customizable **Print-on-Demand (POD) T-shirt Store**. It includes a shader-based animated home page and a fully interactive product customization interface.

---

## 🧩 Features

### 🔮 Part 1 – Animated Home Page
- Pixel-perfect replication of Codrops’ [Repeating Image Transition](https://tympanus.net/Development/RepeatingImageTransition/)
- Implemented using `Three.js` shaders with Lit
- Built-in routing via `@vaadin/router`

### 👕 Part 2 – Product Customization Page
- Upload image to preview on 3D T-shirt
- Switch clothing type via dropdown (T-shirt, Hoodie, Sleeveless, Cap)
- Dynamic texture mapping on GLTF 3D models
- Large & small live preview sections
- Basic size, height, and build selectors

---

## 🛠️ Tech Stack

- [Lit](https://lit.dev/) for components
- [Three.js](https://threejs.org/) for WebGL and shaders
- [@vaadin/router](https://github.com/vaadin/router) for client-side routing
- [Vite](https://vitejs.dev/) for fast dev & build

---
## 🚀 Setup & Run Locally
cd lit-pod-store
npm install
npm run dev
