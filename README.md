# 🏺 2048 Kiln — A Slow-Fired Puzzle Game

> **A responsive, zero-dependency HTML5 implementation of the classic 2048 tile-merging puzzle game, featuring a custom pottery-inspired "Kiln" design system, smooth animations, touch support, and state handling.**

[![HTML5](https://img.shields.io/badge/Language-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/Styling-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/Logic-Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-009B4D?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://opensource.org/licenses/MIT)

---

## 📖 Overview

**2048 Kiln** reimagines the original 2048 puzzle mechanics with an organic, ceramic-inspired aesthetic. Built entirely using vanilla modern web technologies (HTML5, CSS3 Variables, and ES6+ JavaScript), the game transitions tiles through visual stages mirroring unglazed raw clay up to rich glazed pottery as numbers increase.

---

## ✨ Key Features & Highlights

* **🎨 Pottery-Inspired Visual Progression:** Custom color palette shifting dynamically from raw clay (`2`–`8`) to fired terracotta (`16`–`256`) and glazed ceramic (`512`–`2048`).
* **📱 Mobile First & Touch-Enabled:** Native swipe gesture support using passive touch event listeners alongside traditional keyboard inputs.
* **⚡ Zero External Dependencies:** Lightweight single-file architecture running natively in any modern web browser without build tools or external libraries.
* **🎮 Smooth Hardware-Accelerated Animations:** Custom CSS keyframes handling tile appearance (`pop`) and merging scale effects (`merge-pop`).
* **📊 Score Persistence & Game State:** Live score calculator, best score tracking, non-blocking 2048 win overlay, and game-over detection.

---

## 🖼️ Gameplay Preview

<div align="center">

### 🕹️ Web & Mobile Board Interface
![2048 Kiln Showcase](./preview.png)

</div>

---

## 🛠️ Technology Stack & Architecture

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│                           2048 KILN ARCHITECTURE                            │
├──────────────────────┬──────────────────────┬───────────────────────────────┤
│   DOCUMENT & MARKUP  │   PRESENTATION LAYER │   GAME ENGINE LOGIC           │
├──────────────────────┼──────────────────────┼───────────────────────────────┤
│ • HTML5 Semantic API │ • CSS Custom Props   │ • Matrix Sliding Algorithms   │
│ • Viewport Control   │ • CSS Grid / Flexbox │ • Touch/Swipe Math Handlers   │
│ • Embedded Styling   │ • Scale Animations   │ • DOM Mutation Engine         │
└──────────────────────┴──────────────────────┴───────────────────────────────┘
