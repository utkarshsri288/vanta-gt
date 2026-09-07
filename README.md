# VANTA GT - Interactive Automotive Experience

A scroll-driven interactive web experience showcasing the VANTA GT sports concept. Built with video scrubbing synced to viewport scroll progress using GSAP ScrollTrigger, smooth scrolling via Lenis, and dynamic canvas particle effects.

---

## Features

- Scroll-controlled video frame synchronization
- Lenis smooth momentum scrolling
- GSAP ScrollTrigger timeline transitions
- Custom dynamic particle canvas overlay
- Animated typography and real-time numeric counters
- Responsive navigation with progress indicator and HUD speed gauge
- Zero-dependency Node.js static server with HTTP range request support for video streaming

---

## Quick Start

### 1. Run with Node.js
```bash
node server.js
```
or
```bash
npm start
```

Open `http://localhost:3000` in your browser.

### 2. Run with any static server
You can also run this using any static HTTP server (Live Server, serve, etc.):
```bash
npx serve .
```
or with Python:
```bash
python3 -m http.server 3000
```

---

## File Structure

```
.
├── index.html        # Main markup, styles, and animation logic
├── server.js         # Local HTTP server with range request support
├── car.mp4           # Core automotive video sequence
├── favicon.svg       # Vector icon
├── package.json      # Project manifest
└── README.md         # Documentation
```
