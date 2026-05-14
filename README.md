<div align="center">

```
     ╔══════════════════════════════════════════════════════════╗
     ║                                                          ║
     ║        জুনাইদ আহমেদ রুপক — কবিতা সংগ্রহ                ║
     ║                                                          ║
     ╚══════════════════════════════════════════════════════════╝
```

# Junaid Ahmed Rupok — Poetry Collection

*"শব্দের ভেতর লুকিয়ে থাকে এক অন্য পৃথিবী"*
*— "Within words lies another world."*

<br>

[![Version](https://img.shields.io/badge/version-1.0.0-b8860b?style=flat-square&labelColor=1c1108)](.)
[![Poems](https://img.shields.io/badge/poems-11-8b3a0f?style=flat-square&labelColor=1c1108)](.)
[![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-6b4c2a?style=flat-square&labelColor=1c1108)](.)
[![Made with](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-b8860b?style=flat-square&labelColor=1c1108)](.)
[![Language](https://img.shields.io/badge/language-Bengali%20%2F%20বাংলা-8b3a0f?style=flat-square&labelColor=1c1108)](.)

</div>

---

## Overview

A beautifully crafted, single-file web experience presenting **11 original Bengali poems** by poet and creator **Junaid Ahmed Rupok**. The design draws from antique manuscript traditions — parchment textures, golden accents, and classical Bengali typography — creating an atmosphere that honours the written word.

No frameworks. No build step. One file. Open in any browser.

---

## ✦ Features

| Feature | Description |
|---|---|
| **Manuscript Aesthetic** | Soft parchment textures, golden ornaments, and ink-dark backgrounds evoke an antique literary feel |
| **Dual-Language Typography** | Carefully paired Bengali & Latin typefaces — `Noto Serif Bengali`, `Cormorant Garamond`, `IM Fell English` |
| **Scroll-Reveal Animations** | Each poem fades and rises into view as you read, powered by the Intersection Observer API |
| **Sticky Navigation** | Quick-jump links to all 11 poems, always accessible without interrupting the reading flow |
| **Fully Responsive** | Seamlessly adapts from mobile to widescreen — poetry reads beautifully at every size |
| **Zero Dependencies** | No npm, no server, no database — works offline once the Google Fonts load |

---

## 📜 Poems

```
  ┌────┬────────────────────────────────┬──────────────────────────────┐
  │ #  │ Bengali Title                  │ English Translation          │
  ├────┼────────────────────────────────┼──────────────────────────────┤
  │ 01 │ আনন্দে                         │ Joy                          │
  │ 02 │ কারবালা প্রান্তর               │ The Plains of Karbala        │
  │ 03 │ দেবো না                        │ I Will Not Give              │
  │ 04 │ বোধদয়                         │ Awakening                    │
  │ 05 │ হিমির ঘরে কে?                  │ Who Is in Himi's Room?       │
  │ 06 │ ওগো প্রমোদিনী                  │ O Joyful One                 │
  │ 07 │ কে. ডি. ক্লাবে অদ্ভুতুরে রঙ্গ │ Strange Scene at K.D. Club   │
  │ 08 │ দেবী দূর্গা                    │ The Goddess Durga            │
  │ 09 │ ঈশ্বর                          │ God                          │
  │ 10 │ খাবি-দাবি কলকলাবি             │ Eat, Drink & Bubble On       │
  │ 11 │ ঈদ-ই-মিলাদুন্নবী              │ Eid-e-Milad-un-Nabi          │
  └────┴────────────────────────────────┴──────────────────────────────┘
```

---

## 🛠 Built With

- **HTML5** — Semantic, accessible structure
- **CSS3** — Custom properties, Flexbox, Grid, keyframe animations
- **Vanilla JavaScript** — Intersection Observer API for scroll-triggered reveals
- **Google Fonts** — `Noto Serif Bengali` · `Cormorant Garamond` · `IM Fell English` · `Cinzel`

---

## 📁 Structure

```
project/
└── index.html      ← everything lives here
```

Single-file architecture. All CSS and JS are embedded inline.

---

## 🚀 Getting Started

```bash
# 1. Download the file
curl -O https://your-repo/index.html

# 2. Open it
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or simply **double-click** `index.html` in your file explorer. That's it.

> Works in Chrome, Firefox, Safari, and Edge. No build step. No installation.

---

## 🎨 Customisation

### Color Scheme

All colors are defined as CSS custom properties at the top of the `<style>` block:

```css
:root {
  --ink:           #1c1108;   /* primary text & background */
  --parchment:     #f8f1e4;   /* page background           */
  --gold:          #b8860b;   /* accents & ornaments       */
  --rust:          #7a2e0e;   /* poem titles               */
  --sepia:         #6b4c2a;   /* secondary text            */
}
```

### Adding a Poem

Copy any `.poem-card` block in `index.html` and update:

```html
<article class="poem-card" id="p12">
  <div class="poem-number">১২</div>
  <div class="poem-header">
    <h2 class="poem-title-bn">নতুন কবিতা</h2>
    <p class="poem-title-en">New Poem</p>
  </div>
  <!-- poem lines go here -->
</article>
```

Then add a matching link to the sticky nav:

```html
<a href="#p12" class="nav-link">১২ নতুন কবিতা</a>
```

### Changing Fonts

Update the Google Fonts `<link>` in `<head>` and swap the `font-family` values in CSS.

---

## ⚙️ Requirements

| Requirement | Detail |
|---|---|
| Browser | Any modern browser (Chrome 80+, Firefox 75+, Safari 13+, Edge 80+) |
| Server | None required |
| Internet | Only needed to load Google Fonts on first visit |
| Dependencies | None |

---

## 📬 Author

<div>

**Junaid Ahmed Rupok**
*Poet & Creator*

</div>

---

## © License

**All Rights Reserved.**

The poems, text, and creative content within this project are the exclusive intellectual property of Junaid Ahmed Rupok. This work may not be reproduced, distributed, modified, or transmitted in any form without prior written permission from the author.

---

<div align="center">

✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦

*Crafted with care for the Bengali literary tradition.*

</div>
