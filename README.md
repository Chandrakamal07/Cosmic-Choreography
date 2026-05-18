# Cosmic Choreography 🌌
### *Built by Kamal*

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://chandrakamal07.github.io/Planetary-Path-Tracing/)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)](https://github.com/Chandrakamal07/Planetary-Path-Tracing)

**Cosmic Choreography** (also known as Planetary Path Tracing) is an advanced, 100% client-side simulation engine that maps the stunning geometric spirograph patterns created by the relative orbits of our solar system's planets over time. 

By calculating true **Keplerian orbital mechanics**, the application bridges the gap between astrophysics and generative digital art, turning orbital resonances into visual and auditory symphonies.

---

## 🚀 Live Simulation
Explore the orbital patterns instantly in your browser:
👉 **[Launch Cosmic Choreography](https://chandrakamal07.github.io/Planetary-Path-Tracing/)**

---

## 🪐 Core Features

### 📡 Physics & Orbital Engine
*   **Elliptical Orbits (Keplerian Eccentricity):** Simulates true elliptical paths rather than simple circles, adding natural asymmetry and floral structural depth to the visual drawings.
*   **3D Inclination Simulation:** Incorporates real orbital plane inclinations. Lines gracefully fade in opacity as planets travel above or below the ecliptic reference plane (Z-depth fading).
*   **Alternative Reference Frames:** Switch effortlessly between a stationary **Heliocentric** view (Sun at center) and a moving **Geocentric-style** view (Planet 1 Stationary, tracking the relative path of Planet 2).

### 🎨 Visual & Auditory Synthesis
*   **Procedural Deep Space Background:** Generates organic, smooth cosmic nebula clouds and deep starfields with varied star classification colors and ambient light glows.
*   **Dynamic Distance-Mapped Coloring:** Spirograph lines dynamically alter their color spectrum on a responsive HSL gradient based on the instantaneous distance between the two chosen planets.
*   **Sonification ("Music of the Spheres"):** Uses the **Web Audio API** to translate physical cosmic proximity into synthesized sound waves, raising tone frequencies as planets arrive at geometric conjunctions.

### 🎛️ User Workspace Controls
*   **Interactive Time Scrubber:** Scrub or rewind through simulated time history seamlessly to examine specific steps of a geometric pattern creation.
*   **Telemetry Panel:** Displays live calculation vectors including real-time distance loops, an automated **Conjunction Counter**, and structural mathematical data for **Synodic Periods**.
*   **Performance Engineering:** Features an adjustable variable timeline slider and custom threshold boundaries ("Keep Last N Lines") to preserve machine rendering limits.
*   **Production Exports:** High-definition static snapshot export (`.png`) and native video recording pipeline capture (`.webm`) directly from the canvas interface.

---

## 🛠️ Tech Stack & Architecture

This application architecture adheres strictly to **Single-File Web App** principles. There are no server dependencies, build steps, packages, or external CDN dependencies.

*   **Markup & UI Canvas:** HTML5 / Twin Canvas layers (`#starsCanvas` background & `#simCanvas` workspace).
*   **Styling Layer:** Modern Glassmorphism themed design leveraging CSS Custom Variables, backdrop blurs, and radial shadows.
*   **Logic Core:** Raw, uncompiled Vanilla JavaScript (ES6+ Context).
*   **Audio Architecture:** Native Web Audio API Oscillator & Audio Dynamics Gain Nodes.

---

## 📊 Quick-Start Preset Combinations
To view some of the solar system's most legendary geometric alignments, use the **Famous Presets** dropdown or map the following variables manually:

| Planet 1 | Planet 2 | Resulting Geometry / Characteristics |
| :--- | :--- | :--- |
| **Earth** | **Venus** | The famous **8:13 Resonance**, drawing an impeccable 5-petaled parametric rose over an 8-year loop. |
| **Jupiter** | **Saturn** | Traces the massive structural nodes of the **Great Conjunction** patterns over a 60-year scale. |
| **Uranus** | **Neptune** | A hyper-extended, deeply dense structural grid spanning a century of slow-moving deep cosmic dance. |

---

## 💻 Local Setup & Execution

Since the architecture is 100% client-side, execution requires no installation:

1. Clone the repository safely via SSH:
   ```bash
   git clone git@github.com:Chandrakamal07/Planetary-Path-Tracing.git

2. Navigate into the folder directory:
   ```bash
   cd Planetary-Path-Tracing
3. Open `index.html` directly in any modern browser (Chrome, Firefox, Safari, Edge) or spin up a micro local environment server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve

📬 Contact & Support
Developer: Chandrakamal

Email: chandrakamal303@gmail.com

Repository: https://github.com/Chandrakamal07/Planetary-Path-Tracing
