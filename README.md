<p align="center">
  <img src="https://img.shields.io/badge/version-2.0.0-gold?style=for-the-badge" alt="Version 2.0.0"/>
  <img src="https://img.shields.io/badge/type-Single%20Page%20Web%20App-16233F?style=for-the-badge" alt="Single Page Web App"/>
  <img src="https://img.shields.io/badge/build-no%20dependencies%20needed-4C7A5E?style=for-the-badge" alt="No Dependencies Needed"/>
  <img src="https://img.shields.io/badge/data-100%25%20on--device-4A7FB5?style=for-the-badge" alt="100% On-Device Data"/>
  <img src="https://img.shields.io/badge/created%20by-Dhurgham%20ALsaadi-coral?style=for-the-badge" alt="Created by Dhurgham ALsaadi"/>
</p>

<h1 align="center"> BluePrint Studio</h1>

<p align="center">
  <strong>Color · Design · Build</strong><br/>
  A beautiful, mobile-first coloring & creative design studio that runs entirely in the browser.
</p>

<p align="center">
  <i>Paint ready-made buildings by number, engineer your own home from scratch, or sketch anything with a freehand brush — then save it all to your personal gallery.</i>
</p>

---

##  Table of Contents

- [What is BluePrint Studio?](#-what-is-blueprint-studio)
- [ Features](#-features)
- [ App Type](#-app-type)
- [ Built Under the Hood](#️-built-under-the-hood)
- [ Getting Started](#-getting-started)
- [ How to Use](#-how-to-use)
- [ Achievements & Fun](#-achievements--fun)
- [ Privacy & Data](#-privacy--data)
- [ What I Personally Built](#-what-i-personally-built)
- [ Project Structure](#️-project-structure)
- [ Roadmap](#️-roadmap)
- [ Creator](#-creator)
- [ License](#-license)

---

##  What is BluePrint Studio?

**BluePrint Studio** is a delightful, pocket-sized creative app presented inside a realistic phone frame with a notch, a splash screen, and smooth micro-animations. It's designed to feel like a native mobile app, but it's actually a **single self-contained HTML file** — no installation, no server, no build step. Just open it and start creating.

It blends three creative experiences into one polished product:

1. ** Color by Number** — 60+ charming templates of houses, castles, nature scenes, animals, towers, and landmarks, each split into numbered regions waiting for the perfect color from a 35-color architect's palette.
2. ** Design Studio** — A sandbox where you build your own home from scratch using draggable shapes: walls, roofs, doors, windows, chimneys, trees, clouds, fences, pools and more. Select, drag, duplicate, layer, and recolor freely.
3. ** Free Sketch** — A freehand drawing canvas with a real brush, eraser, adjustable stroke size, 35+ colors including a custom color picker, and undo support.

Everything you make can be exported as a **PNG** and saved to your own on-device **My Art** gallery.

---

##  Features

###  Color by Number
- **60+ hand-crafted templates** across 8 themes:
  -  Houses & Homes — *Cozy Cottage, Modern Villa, Mountain Cabin, Red Barn*
  -  Castles & Towers — *Storybook Castle, Knight's Castle, Wizard's Tower, Ice Castle, Fairy Castle*
  -  Nature & Landscapes — *Giant Tree, Mountain Peak, Waterfall, Sunset, Volcano, Desert Dunes*
  -  Animals — *Cute Cat, Friendly Dog, Wise Owl, Brown Bear, Gentle Elephant, Butterfly*
  -  Plants & Gardens — *Sunflower, Bonsai Tree, Rose Bush, Palm Tree, Cactus*
  -  Vehicles & Travel — *Space Rocket, School Bus, Sailing Ship, Helicopter, Airport Terminal*
  -  Buildings & Cities — *Hospital, Library, School, Hotel, Apartment Block, Stadium*
  -  Landmarks & More — *Train Station, Bridge, Koi Pond, Tiered Fountain, Swimming Pool*
- **35-color palette** — from *Brass* to *Lime*, *Mint* to *Thistle*, every shade an aspiring designer needs.
- **Guided mode** — matches each numbered region against the palette so you always pick the right color.
- **Free mode** — toggle it off for total freedom.
- **Smart progress saving** — your in-progress masterpiece is remembered automatically; finish it any day.
- **Satisfying sound effects** — a cheerful chime celebrates every correctly painted region.

###  Design Studio
- **15 draggable shape tools** — Ground, Wall, Roof, Door, Window, Round Window, Chimney, Tree, Sun, Cloud, Fence, Path, Flag, Pool, Lamp.
- **Full drag & drop** — grab any shape and move it anywhere on the 300×400 blueprint canvas.
- **Shape editing** — select, delete, duplicate, and bring-to-front to layer your creation perfectly.
- **Recolor anything** — tap a shape, tap a swatch, and watch it transform.
- **Export to PNG** — save your custom design straight into My Art.

###  Free Sketch
- Freehand brush with smooth pointer drawing.
- Eraser, Undo (up to 15 snapshots), and Clear.
- Adjustable brush size (2–28px).
- Full palette **plus a native color picker** for any custom color.

###  My Art Gallery
- All your completed colorings, custom designs, and sketches live in one personal gallery.
- Saved as **high-quality PNG** data URLs.
- Tap any artwork to preview or delete it.

###  Search
- Real-time search across **all 60+ templates**.
- Smart keyword tags: try `castle`, `tower`, `nature`, `animal`, `nature`, `vehicle`, `building`…

###  Streak & Calendar
- Every day you visit lights up on a beautiful monthly calendar.
- Tracks your **current streak**, **longest streak**, and **total active days**.

###  Trophy Room
- **16 achievements** to unlock:
  -  *First Steps, First Fill*
  -  *Getting Colorful → Color Machine → Color Legend* (25 / 100 / 500 fills)
  -  *Architect in Training → Master Builder → Construction King*
  -  *Streak Starter → Dedicated Designer → Daily Devotee*
  -  *Design Studio Pro → Architect Extraordinaire*
  -  *Collector → Art Gallery → Explorer*
- Progress bars show exactly how close you are to the next badge.

###  More Delights
- **News & Updates** — an in-app changelog.
- **In-app rating & reviews** — 5-star feedback stored on-device.
- **Sound design** — every tap, glide, save, and unlock has its own delightful tone, synthesized live with the Web Audio API (fully toggleable).
- **Smart splash screen** — a spinning compass blueprint with rotating loading tips (*"Rolling out blueprints…"*, *"Counting bricks…"*).
- **Custom confirmation modals** — tasteful, branded dialogs instead of ugly browser popups.

---

##  App Type

**BluePrint Studio is a Single-Page Web Application (SPWA)** — a mobile-first, phone-framed creative studio:

| Property | Value |
|---|---|
| **Type** | Single-page browser application (zero install) |
| **Language** | HTML5 + CSS3 + Vanilla JavaScript (ES6+) |
| **Dependencies** | [Font Awesome](https://fontawesome.com) icons (CDN) only |
| **Build system** | None — open the file, it just works |
| **Backend** | None — fully client-side |
| **Storage** | `localStorage` (all data stays on your device) |
| **Rendering** | Dynamic SVG for templates & studio, `<canvas>` for sketching |
| **Audio** | Web Audio API (synthesized tones, no audio files) |
| **Design** | Mobile-first, phone-device frame, blueprint/navy/brass theme |

It's the kind of app a developer builds as a polished, self-contained product demo — complete with a living product feel: splash, home hub, tabs, streaks, achievements, settings, legal screens, and reviews.

---

##  Built Under the Hood

BluePrint Studio is engineered as a tiny but complete **front-end architecture** in one file:

- **State management** — a central `state` object persists across sessions via a typed `localStorage` wrapper (`LS.get` / `LS.set`).
- **View routing** — a lightweight screen router (`goTo()` → `render()`) with tabbed navigation and stack-style sub-screens (Color → Search → More → Settings…).
- **Template engine** — 60+ parametric templates defined as declarative region arrays (rect / polygon / circle) rendered into interactive SVG.
- **Rendering pipeline** — SVG shapes → standalone SVG → `<canvas>` → `dataURL` PNG export.
- **Audio engine** — a tiny synthesizer (`tone()` + `SFX`) generates chimes, ticks, and fanfares procedurally.
- **Achievement engine** — declarative badge definitions with live progress functions and unlock side-effects.
- **Streak engine** — date-set math for current/longest/day counts with a calendar heat-map view.
- **Interaction polish** — hover lifts, scale presses, shake feedback on wrong answers, glow pulses, toasts, and fade-in-up transitions throughout.

---

##  Getting Started

Because BluePrint Studio is a single HTML file, getting started is *ridiculously* easy:

**Option A — Just open it**
```bash
# Clone the repo
git clone https://github.com/dhurghamCreation/BlueBrintStudio.git
cd BlueBrintStudio

# Open the app in your default browser
start index.html        # Windows
open index.html         # macOS
```

**Option B — Serve it locally (recommended for the full feel)**
```bash
# With Python
python -m http.server 8080
# then visit http://localhost:8080

# Or with Node
npx serve .
```

That's it. No `npm install`, no config, no build step. **Double-click and create.**

>  The app is designed for a phone-like viewport. Open it in a narrow window or your browser's device toolbar for the best "native app" feel.

---

##  How to Use

### 1. Color by Number
1. Tap the **Draw** tab → **Color by Number**.
2. Pick a template from the searchable library (try `castle` or `nature`).
3. A palette of swatches appears with numbers — tap a **number swatch**, then tap the matching **numbered region** on the building.
4. In *Guided mode*, wrong regions give a gentle shake; in *Free mode*, anything goes.
5. Fill every region → **"Building complete!"** → hit **Save Finished Piece** to add it to My Art.

### 2. Design Studio
1. From the Draw hub, tap **Design Studio**.
2. Add shapes from the toolbar (Wall, Roof, Door, Window…).
3. **Click & drag** any shape to move it. Tap to select.
4. Use **Delete**, **Duplicate**, and **Bring Forward** to refine.
5. Pick a color from the palette, then tap a shape to repaint it.
6. Hit **Save Design** to export your dream home to My Art.

### 3. Free Sketch
1. From the Draw hub, tap **Free Sketch**.
2. Choose brush or eraser, pick a color (or the custom picker), adjust size.
3. Draw freely — Undo and Clear are one tap away.
4. **Save Sketch** frees it into your gallery.

### 4. Manage Your Collection
- Visit **My Art** to browse everything you've created.
- Tap any artwork to delete (with a friendly confirmation modal).

### 5. Build Your Identity
- Visit every day to keep your **streak** alive.
- Check the **Trophy Room** to see unlock progress.
- Rate the app under **More → Rate & Review**.

---

##  Achievements & Fun

| Badge | Requirement |
|---|---|
|  First Steps | Open the app once |
|  First Fill | Color your first region |
|  Getting Colorful | Fill 25 regions |
|  Color Machine | Fill 100 regions |
|  Color Legend | Fill 500 regions |
|  Architect in Training | Complete 1 template |
|  Master Builder | Complete 5 templates |
|  Construction King | Complete 25 templates |
|  Streak Starter | 3-day streak |
|  Dedicated Designer | 7-day streak |
|  Daily Devotee | 30-day streak |
|  Design Studio Pro | Create 5 custom designs |
|  Architect Extraordinaire | Create 20 custom designs |
|  Collector | Save 10 drawings |
|  Art Gallery | Save 50 drawings |
|  Explorer | Complete 10 different templates |

---

##  Privacy & Data

Your creativity belongs to you — **100% of your data stays on your device.**

-  **No accounts, no tracking, no cookies, no server.**
-  All drawings, streaks, achievements, and settings are stored in your browser's `localStorage`.
-  The app includes an explicit **Privacy & Consent** screen.
-  You can wipe everything anytime via **Settings → Reset all app data**.

---

##  What I Personally Built

This project was crafted by hand, piece by piece, to feel like a real shipping product:

- **The complete concept & design language** — the navy + brass + paper "blueprint" aesthetic, the phone-device presentation, and the *Color · Design · Build* identity.
- **The full UX architecture** — six-tab navigation, screen router, top-bar header system with back-stack behavior, splash-to-app boot sequence, and toast notifications.
- **All 60+ color-by-number templates** — every cottage, castle, cat, cactus, and rocket ship was authored as parametric geometry (rect/polygon/circle regions) with careful composition.
- **The SVG → PNG export pipeline** — building standalone SVG markup, rasterizing it through a canvas, and persisting high-quality images to the gallery.
- **The interactive Design Studio** — pointer-based drag & drop with canvas-coordinate math, selection, duplication, layering, and per-shape recoloring.
- **The Free Sketch engine** — a full pointer-drawing canvas with brush/eraser/undo/clear and a custom color input.
- **The achievement & streak systems** — declarative badge definitions, live progress computation, unlock toasts, and the calendar heat-map.
- **The procedural audio engine** — Web Audio API synth that generates every tap, chime, save, and fanfare without a single audio file.
- **The in-app polish** — custom confirmation modals, shake animations on mistakes, glow pulses, hover mechanics, and micro-interactions on every touchpoint.
- **The product extras** — News & Updates feed, in-app ratings & reviews, Terms, and the Privacy & Consent screen.

---

##  Project Structure

```
BluePrint Studio
│
└──  BlueBrintStudio
    └──  index.html          ← The entire app (HTML + CSS + JS)
    │
    ├──  60+ templates        (declared in-app)
    ├──  35-color palette     (in-app)
    ├──  16 achievements      (in-app)
    └──  localStorage         (on-device persistence)
```

Everything — markup, styles, logic, data, and audio — lives in a single `index.html` file. Extreme portability: copy it to a USB stick, email it to a friend, or host it anywhere.

---

##  Roadmap

Ideas brewing for future editions:

-  **More templates** — spaceships, underwater scenes, villages, and holidays.
-  **Custom palettes** — save your own favorite color sets.
-  **Backgrounds** — add sky, night, or sunset backdrops to sketches.
-  **Undo in Design Studio** — full history for every shape action.
-  **Share gallery** — export entire My Art collections as one image sheet.
-  **Challenges** — daily color puzzles and timed design duels.
-  **PWA packaging** — installable offline experience.
-  **Multi-language** — localize the studio for a global audience.

---

##  Creator

**BluePrint Studio was created by [Dhurgham ALsaadi](https://github.com/dhurghamCreation)** — crafted with care, love, and an unhealthy amount of Brass `#D4A24E` pigment. 

This README and the product it documents were built by **Dhurgham ALsaadi** with the assistance of **Cline** (an AI-powered engineering assistant).

---

##  License

This is a personal, demonstration project. While it's public for learning and inspiration, please reach out to the creator before reusing the templates, art, or branding commercially.

---

<p align="center">
  <img src="https://img.shields.io/badge/%20Keep%20Coloring-🏗%20Keep%20Building-4A7FB5?style=for-the-badge" alt="Keep Coloring, Keep Building"/>
</p>

<p align="center">
  <sub><b>BluePrint Studio v2.0.0</b> · Color · Design · Build</sub>
</p>
