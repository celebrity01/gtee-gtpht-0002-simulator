# GTEE GTPHT-0002 — Electro-Pneumatic Interactive Simulator

An interactive 3D electro-pneumatic training workbench simulation built with **Three.js**.

## Features

- 🔧 **3 Rendering Modes** — Physical, Full Working, and Transparent (glass cutaway view)
- 🎮 **Real-time Simulation** — Extend/retract cylinders, fire solenoid valves, trigger auto-cycle sequences
- 🎨 **High-fidelity PBR Materials** — Clearcoat metals, transmission glass, IBL environment reflections
- 💡 **Studio Lighting** — 6-light rig with 4096px shadow maps and rim lighting
- 🔊 **Audio Feedback** — Web Audio API pneumatic hisses and relay click sounds
- 📷 **Camera Presets** — 6 smooth-tweened camera angles

## Live Demo

Deployed on [Vercel](https://vercel.com)

## Run Locally

`ash
python -m http.server 8000
`
Then open http://localhost:8000
