# 🧩 Puzzle Pop

A warm, playful photo puzzle — turn any picture into a jigsaw, drag the pieces into place, and watch it come together.

**▶️ Live app:** https://ratanpriyapandey.github.io/Puzzel-game/

---

## What it does

- 🖼️ **Use your own photo** — tap **📷 Photo** to pick any picture from your device (it stays on your device — nothing is uploaded).
- 🎚️ **Three difficulty modes** — 🐶 Easy (9 pieces), 🦄 Medium (16), 🧩 Hard (25).
- ✋ **Drag to solve** — drop pieces anywhere; they swap freely. A green ✓ marks each piece that's in the right place.
- 👁 **Picture guide** — reveal a faint version of the full picture under the tiles when you get stuck.
- 💡 **Hint** — highlights where the next piece goes.
- 🎉 **Completion** — finish the puzzle and the picture pops with a little celebration.

Built to feel good on a **touchscreen** (works great on an iPad) and with a mouse.

## How to run it

**Online:** just open the live link above.

**Locally:** download the files and open `index.html` in any modern browser.

**Add to your phone/tablet home screen (app-like):**
1. Open the live link in **Safari** (iOS) or **Chrome** (Android).
2. Tap **Share → Add to Home Screen**.
3. Launch it from the new icon — it opens full-screen like an app.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app — HTML, CSS, and JavaScript in one self-contained file (the photos are embedded). |
| `manifest.webmanifest` | Web-app metadata (name, icon, colors) so it can be installed to the home screen. |
| `icon.svg` | The app icon. |
| `sw.js` | Service worker. *(Currently a clean-up "kill-switch" — offline caching is disabled while the app is being actively developed, so devices always load the newest version.)* |

## Tech

- Plain **HTML + CSS + JavaScript** — no framework, no build step, no dependencies.
- Pointer Events for smooth touch + mouse dragging.
- Hosted free on **GitHub Pages**.

## Roadmap ideas

- Re-enable offline support once the design is stable.
- Save/share a finished puzzle.
- More themes and photo packs.

---

*A personal project — made for fun.*
