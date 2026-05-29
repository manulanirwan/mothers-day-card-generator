# 🌷 Mother's Day Card Generator

An elegant, fully responsive single-page web application designed to help users create and download high-quality, personalized Mother's Day cards. Built with pure vanilla frontend technologies, this tool integrates client-side image cropping, real-time typography scaling, and vector graphic framing overlays.

---

## 🚀 Features

* **Elegant Accent Framework:** Features procedurally generated dual-layered border vectors and interlocking graphic accent squares at the outer edges for a polished stationary feel.
* **Dynamic Photo Masking:** Accepts any device photo, scales it down from its true geometric center, and overlays a smooth 20px rounded-edge clipping mask to eliminate clipping distortion.
* **4 Dedicated Style Palettes:** Switch between four pre-configured presentation layouts on the fly:
  * **Elegant Pink:** Soft pastel backdrops with rich rose accents.
  * **Golden Blossom:** Minimalist warm cream surfaces paired with luxury gold frame profiles.
  * **Royal Rose:** High-contrast clean backdrops with deep maroon borders.
  * **Vintage Minimal:** Earthy, organic taupe tones for a modern, rustic touch.
* **Smart Typography Layout Engine:** Implements a dynamic canvas text-wrapping loop that calculates line widths sequentially to accommodate longer messages without layout overflow.
* **Local PNG Downloads:** Instantly compiles and exports the graphics canvas layer directly to your local file system as a `Mothers_Day_Card.png`.
* **Scoped Embedding Support:** Optimized with specific CSS prefixes to ensure seamless embedding into standard blog platforms (such as Blogger themes) without overriding external container layouts.

---

## 🛠️ Tech Stack

* **HTML5:** User control interface forms and the foundational layout canvas node (`<canvas>`).
* **CSS3:** Flexible grid alignments, responsive viewport breakpoints, and interactive hover transformations.
* **JavaScript (ES6+):** * `FileReader API` for serverless local data loading.
  * `HTML5 Canvas API` for dynamic context redrawing (`roundRect`, `fillRect`, `measureText`, and clipping loops).

---

## 📦 Getting Started

This repository runs independently of servers, node modules, or build configurations.

1. Clone this repository locally:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/mothers-day-card-generator.git](https://github.com/YOUR_USERNAME/mothers-day-card-generator.git)
