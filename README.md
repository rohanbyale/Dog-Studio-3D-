

### **Thech Stack**

![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.dot-js&logoColor=white)
![React Three Fiber](https://img.shields.io/badge/R3F-000000?style=for-the-badge&logo=react&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL-44CC11?style=for-the-badge&logo=opengl&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)


## 🚀 Technical Core

### 🎨 Creative Coding & Shaders
The "soul" of this project lies in its custom GLSL implementation. Rather than relying on standard meshes, I’ve implemented:
*   **Vertex Shaders:** For organic mesh deformation and wave-like displacement.
*   **Fragment Shaders:** To calculate real-time **Fresnel lighting** and custom noise-based textures.
*   **Post-Processing:** A custom pipeline using `EffectComposer` to add Bloom, Grain, and Chromatic Aberration for a cinematic finish.

### ⚛️ React 3D Architecture
Built using **React Three Fiber (R3F)** to maintain a declarative structure while handling imperative 3D logic:
*   **Optimization:** Using `Preload` and `AdaptiveEvents` from Drei to ensure 60FPS on varying hardware.
*   **State-Driven Animation:** Linking 3D transforms to React state and scroll position.
*   **Asset Pipeline:** Optimized `.glb` models compressed with Draco for lightning-fast initial loads.

---

## 🛠️ Built With

| Tech | Purpose |
| :--- | :--- |
| **React + Vite** | Core UI and ultra-fast development environment. |
| **Three.js** | The underlying 3D engine. |
| **React Three Fiber** | Bridging React state to the Three.js scene graph. |
| **GLSL** | Raw shader language for custom lighting and distortions. |
| **GSAP** | For complex, timeline-based sequencing and "scrub" animations. |
| **Framer Motion** | Handling UI transitions and micro-interactions in the DOM. |

---
