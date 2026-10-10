# Me and Spidey 🕷️

> *"I'm not Peter Parker because I already know what I'm capable of. I relate to him because, like him, I'm still discovering it."*

An interactive, high-performance portfolio and scroll-driven animation showcase by **Meer Mohammed Shoaib**, built with **GSAP**, **ScrollTrigger**, and a hardware-accelerated **4K Canvas Sequence Engine**.

---

## 🌟 Highlights & Features

- **Fluid 4K Sequence Scrubbing**: 264 ultra-HD frames cached directly into GPU memory with aspect-ratio cover math and sub-pixel alignment.
- **Retina Display Clarity**: High-DPI backing store scaling with `window.devicePixelRatio` for razor-sharp rendering on modern displays.
- **Peter Parker Philosophy Narrative**: 5 cinematic HUD story cards that fade into view during the dive:
  1. *01 // The Builder Mindset* — Turning curiosity into working code (ELI5, NetSentry, DevKit).
  2. *02 // Polymath Curiosity* — Crossing disciplines from Cybersecurity to AI and Creative Web.
  3. *03 // Relentless Craft* — Never settling for software that merely works.
  4. *04 // Empirical Iteration* — Learning by making mistakes, debugging, and first-principles thinking.
  5. *05 // The Leap of Faith* — Still becoming who I want to be.
- **Grand Finale Climax**: The surprise finale card appears directly inside the golden sunset climax frames, featuring interactive replay and social connects.
- **Hardware-Accelerated Performance**: RequestAnimationFrame render loop with zero redundant redraws (`if (idx === lastRenderedFrame) return`).

---

## 🚀 Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/meer-md-shoaib/Me-and-spidey.git
   cd Me-and-spidey
   ```

2. Start the local server:
   ```bash
   node server.js
   ```

3. Open your browser at:
   ```
   http://127.0.0.1:3000
   ```

---

## 🛠️ Tech Stack

- **GSAP 3** & **ScrollTrigger**
- **HTML5 Canvas 2D API** (Retina DPR Scaling)
- **Vanilla CSS** (Stark-inspired Glassmorphism)
- **Node.js** (Streaming Static Server)

---

## 📬 Connect

- **LinkedIn**: [Meer Mohammed Shoaib](https://linkedin.com/in/MeerMohammedShoaib)
- **GitHub**: [@meer-md-shoaib](https://github.com/meer-md-shoaib)
