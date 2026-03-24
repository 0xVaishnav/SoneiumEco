# 🌐 Soneium Interactive Architectures


An immersive, browser-based 3D visualization of decentralized networks, featuring real-time interactive physics, computer vision hand-tracking, and cinematic post-processing.

## ✨ Features
* **Multi-Chain Topologies:** Hot-swap between the visual architectures of **Startale**, **Soneium**, and **Astar**.
* **Dual-Input Tracking Engine:** * **📷 Camera Mode:** Uses Google's MediaPipe to track hand gestures. Pinch to elastically expand the network nodes.
  * **🖱️ Mouse Mode:** Projects a 3D raycast into the scene, creating a magnetic repulsion field that physically parts the data lines as you move.
* **Unreal Bloom Post-Processing:** Implements Three.js `EffectComposer` to create ambient, glowing data streams without washing out the core gradients.
* **Cinematic Parallax:** The entire 3D camera shifts dynamically with mouse movement to create deep spatial volume.

## 🛠️ Tech Stack
* **Three.js (WebGL):** 3D Rendering, Instanced Meshes, and Post-Processing.
* **MediaPipe:** Real-time AI Hand Tracking.
* **Vanilla JavaScript:** Zero heavy frameworks; pure frontend performance.

## 🚀 How to Run Locally
Because this project uses the HTML5 Canvas API to scan exact pixel colors from local images, it requires a local web server to bypass strict CORS security rules.

1. Clone this repository:
   ```bash
   git clone [https://github.com/0xVaishnav/SoneiumEco.git](https://github.com/0xVaishnav/SoneiumEco.git)