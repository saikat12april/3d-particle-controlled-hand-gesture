# 🧠 Gesture Controlled 3D Particle System

An immersive, real-time 3D particle experience that reacts to your hand gestures via webcam.  
Morph between multiple geometric shapes, control particle expansion, and enjoy dynamic zoom — all with just your hand.

🌐 **Live Demo:** [https://saikat12april.github.io/3d-particle-controlled-hand-gesture/](https://saikat12april.github.io/3d-particle-controlled-hand-gesture/)

![Particle Demo](https://via.placeholder.com/800x400?text=Gesture+Particle+Universe) *(add a screenshot or GIF of your project here)*

---

## ✨ Features

- **9 Unique Particle Shapes** – Sphere, Heart, Saturn Ring, Flower, Supernova, Torus Knot, Star Crown, Cosmic Wave, Diamond Grid.
- **Real‑time Hand Tracking** – Powered by MediaPipe Hands.
- **Intuitive Gesture Controls**:
  - ✋ **Open Hand** → Expand & morph particles.
  - ✊ **Closed Fist** → Return to a dense Sphere.
  - ✌️ **Peace Sign** → Cycle through all shapes.
- **Dynamic Zoom & Scale** – Move your hand closer/farther from the camera to zoom in/out; particles grow larger when zoomed in.
- **Hand Influence Field** – Your hand’s position pushes/pulls particles in real time.
- **High‑Performance** – 21,000 glowing particles with additive blending and custom shaders.
- **Responsive UI** – Glass‑morphism instruction panel + mirrored webcam feed.

---

## 🎮 How to Use

1. Allow camera access when prompted.
2. Show your hand clearly in the webcam view (bottom‑right corner).
3. Use the gestures described above to control the particle system.
4. Move your hand around – the particles will follow and react.

> 💡 **Tip:** Good lighting and a plain background improve hand tracking accuracy.

---

## 🛠️ Tech Stack

| Technology       | Purpose                              |
|------------------|--------------------------------------|
| Three.js (r128)  | 3D rendering, particle system        |
| MediaPipe Hands  | AI hand landmark detection           |
| GLSL Shaders     | Custom vertex/fragment shaders for glow & morph |
| JavaScript (ES6) | Gesture logic & animation loop       |

---

## 📦 Local Development

To run the project locally:

```bash
git clone https://github.com/saikat12april/3d-particle-controlled-hand-gesture.git
cd 3d-particle-controlled-hand-gesture
# Serve with any local server (e.g., live-server, python -m http.server)
python -m http.server 8000
