# GestureNova ✨
### Hand-Powered Particle Universe using Computer Vision

GestureNova is an interactive **3D particle visualization system** controlled entirely by **hand gestures**. Using real-time **computer vision**, users can manipulate thousands of particles in the browser to generate dynamic shapes, color shifts, and particle explosions.

This project combines **MediaPipe hand tracking**, **Three.js WebGL rendering**, and **custom GPU shaders** to create a gesture-controlled visual experience.

---

## 🌐 Live Demo
Try it here:

https://yourusername.github.io/gesture-nova

*(Allow camera access when prompted)*

---

## 🎮 Controls

| Gesture | Action |
|-------|-------|
| 👍 Thumbs Up | Next particle shape |
| ✌️ Peace Sign | Previous shape |
| 🤌 Pinch | Particle explosion |
| ↔ Move hand left/right | Change particle color |

---

## ✨ Features

- Real-time **hand gesture recognition**
- **18,000 GPU-accelerated particles**
- Smooth **shape morphing animations**
- Dynamic **color control with hand motion**
- Interactive **particle explosion effects**
- Multiple procedural particle structures
- Full-screen immersive visualization

---

## 🔷 Particle Shapes

GestureNova currently supports multiple particle formations:

- ❤️ Heart
- 🪐 Saturn
- 🌸 Bloom
- 🧬 DNA
- 🌌 Galaxy
- 🧊 Cube
- ⭐ Star

Particles smoothly morph between shapes using GPU shader interpolation.

---

## 🧠 Tech Stack

- JavaScript
- Three.js
- MediaPipe Hands
- WebGL (GLSL shaders)
- HTML5
- CSS3

---

## ⚙️ How It Works

1. **MediaPipe Hands** detects and tracks hand landmarks using the webcam.
2. Landmark coordinates are analyzed to detect gestures such as **pinch, thumbs-up, and peace signs**.
3. Gesture data controls a **Three.js particle system**.
4. Custom **GLSL shaders** animate particle motion, color, and shape morphing.
5. The result is a **gesture-controlled particle universe** rendered in real time.

---

## 🚀 Running the Project

1. Clone the repository
