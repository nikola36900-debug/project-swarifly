<div align="center">

  <!-- Custom Geometric Fountain-Pen Nib & 'S' Monogram SVG -->
  <svg width="72" height="84" viewBox="0 0 80 96" fill="none" xmlns="http://www.w3.org/2000/svg">
    <rect width="80" height="96" rx="4" fill="#111111"/>
    <path d="M40 10L66 48L55 82H25L14 48L40 10Z" stroke="#ECEBE8" stroke-width="2.4" stroke-linejoin="miter"/>
    <line x1="40" y1="10" x2="40" y2="44" stroke="#D81E1E" stroke-width="2.2"/>
    <circle cx="40" cy="48" r="4.5" fill="#D81E1E"/>
    <path d="M47 59H33.5V66.5H46.5V74H33" stroke="#ECEBE8" stroke-width="2.2" stroke-linecap="square"/>
  </svg>

  <h1>SWARIFLY®</h1>
  <p><strong>FINE STATIONERY & ARCHITECTURAL DESK OBJECTS</strong></p>
  <p><em>A Swiss Brutalist & Editorial Single-Page E-Commerce Experience</em></p>

  <p>
    <img src="https://img.shields.io/badge/ARCHITECTURE-SINGLE_FILE_HTML5-111111?style=for-the-badge" alt="HTML5" />
    <img src="https://img.shields.io/badge/STYLING-TAILWIND_CSS_CDN-ECEBE8?style=for-the-badge&labelColor=111111" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/MOTION-VANILLA_JS_&_SVG-D81E1E?style=for-the-badge" alt="Motion" />
    <img src="https://img.shields.io/badge/LICENSE-MIT-111111?style=for-the-badge" alt="MIT License" />
  </p>

  <p>
    <a href="#-overview">Overview</a> •
    <a href="#-design-system--tokens">Design System</a> •
    <a href="#-motion--svg-architecture">Motion & SVG</a> •
    <a href="#-curated-catalog-index">Catalog</a> •
    <a href="#-getting-started">Getting Started</a>
  </p>

</div>

---

## `01` — OVERVIEW

**SWARIFLY®** is a zero-dependency, editorial e-commerce storefront crafted for a luxury stationery and architectural desk object studio. Inspired by mid-century Swiss typographic grids and high-contrast monochrome print magazines, the interface pairs oversized condensed display typography with tactile cotton-paper textures, custom geometric SVG iconography, and bold crimson geometric accents.

> *"We turn thoughts into tangible artifacts that last."*

### ✨ Core Highlights
- **Custom Geometric Nib & 'S' SVG Brand Mark**: Integrated into the ink-drop preloader curtain, sticky header, and footer with interactive stroke-draw hover animations.
- **Swiss Editorial Motion System**: Includes a `1.2s` preloader curtain reveal, `IntersectionObserver` staggered scroll animations, scroll-linked parallax on the hero crimson sphere and swirling ink art, an infinite ticker marquee, and magnetic CTA buttons.
- **Full Storefront Interactivity**: Live category filtering, product specification quick-view modal, slide-over archive shopping bag with quantity adjustments, and a bespoke atelier commission modal.

---

## `02` — DESIGN SYSTEM & TOKENS

### 🎨 Color Palette

| Token | Hex | Swatch | Role & Usage |
| :--- | :--- | :---: | :--- |
| **Warm Stone** | `#ECEBE8` | ![#ECEBE8](https://img.shields.io/badge/-%23ECEBE8-ECEBE8?style=flat-square) | Primary canvas background & cotton rag paper base |
| **Archival Card** | `#E4E2DD` | ![#E4E2DD](https://img.shields.io/badge/-%23E4E2DD-E4E2DD?style=flat-square) | Secondary surface panels & specification containers |
| **Matte Ink** | `#111111` | ![#111111](https://img.shields.io/badge/-%23111111-111111?style=flat-square) | Primary typography, `1px` structural rules & monochrome frames |
| **Vermilion Crimson** | `#D81E1E` | ![#D81E1E](https://img.shields.io/badge/-%23D81E1E-D81E1E?style=flat-square) | Hero geometric focal sphere, CTAs & active indicators |

### ✒️ Typography Hierarchy

| Role | Typeface | Weight / Style | Application |
| :--- | :--- | :--- | :--- |
| **Display Mega** | `Anton` | `400` / Uppercase / `0.90` Leading | Hero & section headlines (`IDEAS IN INK`, `MORE THAN PAPER`) |
| **Editorial UI** | `Inter` | `300` – `800` / Tight Tracking | Navigation links, product titles & body copy |
| **Technical Index** | `JetBrains Mono` | `400` – `500` / Monospace | Catalog indices (`001`–`006`), coordinates (`25.5788° N`) & badges |
| **Handwritten Note** | `Caveat` | `700` / Tilted `-12deg` | Organic editorial annotations (`Write Bigger`) |

---

## `03` — ARCHITECTURAL WIREFRAME

```text
┌──────────────────────────────────────────────────────────────────────┐
│ [NIB] SWARIFLY®   FINE STATIONERY   CATALOG | BESPOKE | ABOUT | BAG  │
├──────────────────────────────────┬───────────────────────────────────┤
│  01 / 04                         │                       Write       │
│                                  │                      Bigger       │
│  IDEAS                           │             ╭───────╮             │
│  IN INK                          │            │ CRIMSON │            │
│                                  │            │  CIRCLE │            │
│  [ EXPLORE OBJECTS → ]           │             ╰───────╯             │
├──────────────────────────────────┴───────────────────────────────────┤
│ ░░ SWARIFLY® ARCHIVAL PAPER • SOLID BRASS INSTRUMENTS • PIGMENT INK ░│
├──────────────────────┬───────────────────────────┬───────────────────┤
│  02 ABOUT            │                           │  CATEGORIES       │
│  MORE THAN PAPER     │   [ MONOCHROME PHOTO ]    │  • Fountain Pens  │
│  LEARN MORE →        │                           │  • Notebooks      │
├──────────────────────┴───────────────────────────┴───────────────────┤
│  03 SELECTED OBJECTS                           [ ALL | PENS | PAPER ]│
│  ┌──────────────┐     ┌──────────────┐     ┌──────────────┐          │
│  │  001 • $145  │     │  002 • $38   │     │  003 • $62   │          │
│  │ OBSIDIAN NIB │     │ MONOLITH A5  │     │  AXIS RULER  │          │
│  └──────────────┘     └──────────────┘     └──────────────┘          │
├──────────────────────────────────┬───────────────────────────────────┤
│  LET'S WRITE TOGETHER   ───►     │   [ SWIRLING INK MACRO PHOTO ]    │
│  [ CONTACT US → ]                │                25.5788° N 91.89° E│
└──────────────────────────────────┴───────────────────────────────────┘
```

---

## `04` — MOTION & SVG ARCHITECTURE

| Feature | Implementation | Visual Behavior |
| :--- | :--- | :--- |
| **Ink-Drop Preloader** | SVG `stroke-dashoffset` keyframe animation + CSS curtain translate | Draws the geometric fountain pen nib and `'S'` monogram on a `#111111` sheet before sliding upward after `1.2s`. |
| **Interactive Brand Mark** | Inline `<svg>` with `.brand-logo-group:hover` stroke animation | Re-draws the pen nib silhouette and shifts the breather hole and outline to `#D81E1E` on hover. |
| **Scroll Reveals** | Native `IntersectionObserver` (`threshold: 0.12`) | Staggers section blocks and product cards upward (`28px` → `0px`) as they enter the viewport. |
| **Dual Scroll Parallax** | Passive `scroll` listener with `will-change: transform` | Shifts the hero crimson focal sphere and closing swirling ink artwork at subtle opposing depths. |
| **Magnetic CTAs** | Pointer `mousemove` offset calculation | Primary buttons (`EXPLORE OBJECTS`, `CONTACT US`) subtly gravitate toward the cursor on hover. |
| **Editorial Marquee** | Infinite CSS `@keyframes` horizontal loop | Continuous Swiss specification ticker that pauses cleanly on pointer hover. |

---

## `05` — CURATED CATALOG INDEX

| Index | Edition Name | Category | Price | Architectural Specifications |
| :---: | :--- | :--- | :---: | :--- |
| `001` | **OBSIDIAN NIB** | Fountain Pen | `$145` | 14K Ruthenium-Plated Nib • Matte Anodized Brass Barrel |
| `002` | **MONOLITH A5** | Cotton Notebook | `$38` | 192 Pages • 120gsm Japanese Cotton Paper • Lay-Flat Smyth-Sewn |
| `003` | **AXIS RULER** | Brass Instrument | `$62` | 200mm Solid C360 Brass • Beveled Anti-Smudge Ink Edge |
| `004` | **CRIMSON VERMILION** | Archival Ink | `$28` | 50ml Heavy Flint Glass • Pigment-Rich pH-Neutral Formula |
| `005` | **DATUM STAND** | Desk Architecture | `$85` | CNC-Milled Anodized Aluminum • 72° Sculptural Pen Angle |
| `006` | **SEAL & STAMP** | Bespoke Wax Kit | `$54` | Engraved Brass Die • 3 Crimson Wax Sticks • Rosewood Handle |

---

## `06` — PROJECT STRUCTURE

```text
swarifly-stationery/
├── index.html          # Complete single-file storefront (HTML5, Tailwind CDN, SVG & Motion JS)
└── README.md           # Project documentation, design tokens & architecture guide
```

---

## `07` — GETTING STARTED

Because **SWARIFLY®** is engineered as a zero-build, single-file web application, you can run or deploy it immediately without Node.js, bundlers, or package installations.

### Local Development
```bash
# 1. Clone the repository
git clone https://github.com/your-username/swarifly-stationery.git

# 2. Navigate into the project directory
cd swarifly-stationery

# 3. Open directly in your browser (or use VS Code Live Server)
open index.html
```

### One-Click Static Deployment
- **GitHub Pages**: Push `index.html` to your `main` branch and enable **Settings → Pages → Deploy from a branch**.
- **Vercel / Netlify**: Drag and drop the project folder or connect your repository with zero build commands required.

---

## `08` — LICENSE

Distributed under the **MIT License**. See `LICENSE` for more information.

<div align="center">
  <br />
  <sub><strong>SWARIFLY® ATELIER</strong> — <em>Est. 2018</em> • <code>25.5788° N, 91.8933° E</code></sub>
</div>