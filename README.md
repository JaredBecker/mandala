# ✦ MANDALA

*drawn by your cursor*

A living mandala that blooms from the motion of your mouse — symmetry, color, and light, generated in real time and set to a synthwave drift. No install, no build step, no dependencies to wrangle. One HTML file, one canvas, infinite pattern.

**[→ Enter the mandala](https://jaredbecker.github.io/mandala/)**

---

### ✦ how it works

Every stroke you draw is mirrored and rotated around the center of the canvas — 2 to 60 times over, with an optional mirror reflection on top. Speed becomes brush weight. Direction becomes color drift. What emerges is never quite the same twice.

- **Shape** — symmetry count, mirror reflection, stroke style (flowing line, glowing ribbon, stippled dots, sparkle burst), chaos jitter
- **Motion** — brush size, cursor-speed reactivity, pulsing brush, sparkle dust, ambient auto-rotate
- **Color** — rainbow cycle, radial gradient, or solid color across five palettes (full spectrum, sunset, ocean, forest, gold monochrome), adjustable glow
- **Trail & canvas** — fading laser trail or a permanent one, custom background
- **Presets** — Neon Dream, Golden Bloom, Deep Ocean, Chaos Bloom, or hit 🎲 *Surprise me*
- **Music** — an ambient synthwave loop starts the moment you begin, with its own play/pause and volume

Move your cursor. Watch it become the brush.

---

### ✦ running it locally

No build, no server, no npm install. Just open it.

```bash
git clone https://github.com/JaredBecker/mandala.git
cd mandala
open index.html   # or just double-click it
```

Everything — markup, styles, and the [p5.js](https://p5js.org/)-powered sketch — lives in a single `index.html`.

---

### ✦ tech

- [p5.js](https://p5js.org/) for the canvas and drawing loop
- YouTube IFrame API for the ambient soundtrack
- Vanilla JS/CSS — no framework, no bundler, nothing to compile

---

<p align="center">✦ ✦ ✦</p>
