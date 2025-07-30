# LATENT NEWS ROOM

This is a local prototype of a media art installation exploring the manipulation of news and reality through political alignment. Two discrete sliders determine the orientation of the video news stream. As users move between political axes (economic: left↔right, social: progressive↔conservative), the played video changes — always continuing at the same relative time point.

---

## 🚀 Getting Started

### 1. Prerequisites

Ensure you have installed:

- [Node.js (LTS)](https://nodejs.org/)
- `npm` (comes with Node.js)

---


### 2. Install Dependencies

```bash
npm install
```

---

### 3. Start the App

```bash
npm run dev
```

Open in your browser:

```
http://localhost:5173
```

---

## 📦 Project Structure

```
installation-app/
├── public/
│   └── videos/
├── src/
│   ├── components/
│   │   ├── VideoPlayer.tsx
│   │   └── SliderPanel.tsx
│   ├── data/
│   │   └── videoMap.ts
│   ├── App.tsx
│   └── main.tsx
├── index.html
├── package.json
└── README.md
```

---

## ⚙️ Features

* Seamless switching between videos with synced relative playback time
* Two discrete sliders representing political axes
* Local-only setup, no backend or internet needed

---

## ✨ Next Steps / Ideas

* Style with Tailwind or custom UI
* Add visual filters (glitch effects, color shifts) per slider position
* Maybe add an Advertisement right after switching to make the switching appear natural

---

## 🧠 Concept

Developed as part of the **"AI in Arts"** project

