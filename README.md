# Molly House Helper

A mobile-first web companion for [**Molly House**](https://wehrlegig.com/products/molly-house) by Wehrlegig Games (Jo Kelly, Cole Wehrle, Drew Wehrle).

No installation. No build step. Open the HTML files directly in a browser.

---

## Files

### `molly-house-helper.html` — Interactive Phase Helper

Tap where you are in the game and get a step-by-step checklist for that phase.

**Features:**
- **Phase picker** — jump directly to Setup, Your Turn, Festivity, End of the Week, Game End, or the Reference drawer
- **State bar** — set player count (2–5), current week (1–5), and tap houses to mark them raided; all persisted to `localStorage` across sessions
- **Conditional steps** — rules that only apply in certain situations (Dangerous Cruising, festivity round count, joy thresholds) appear or disappear based on your current state
- **Inline quotes** — key rulebook passages shown at the relevant step with page numbers
- **Reference drawer** — slide-up panel covering the cross-cutting rules players most often forget (exposure paths, Most Infamous vs Most Reputation, molly bonus, foiling/Pride Rule, item timing, joy thresholds, informers)
- **Reset button** — clears all state back to defaults

### `molly-house-reference.html` — A4 Print Reference Sheet

A single-page quick reference designed to sit on the table during play. Print with **Background graphics** enabled for best results (Cmd+P on Mac).

Covers: phase sequence, all exposure triggers, festivity ranking & bonuses, End of the Week steps, all 6 items with timing windows, joy thresholds, game endings, and house/suit mapping.

---

## How to use

Open `molly-house-helper.html` in a mobile browser (or desktop browser in mobile-emulation mode). State saves automatically — just set your player count and week at the start of the session.

The reference sheet works standalone or alongside the app.

---

## Rules source

All content is sourced from the PDFs in `Molly house game/`:
- `Rules and Aids/Molly House Rules.pdf`
- `Rules and Aids/Molly House Player Aids (Front).pdf`
- `Rules and Aids/Molly House Player Aids (Backs).pdf`
- `Board and Playmat/Molly House Gameboard Full Size.pdf` (joy track thresholds)

---

## License

Game rules and materials © Wehrlegig Games, licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). This companion app is a non-commercial personal aid made under the same licence terms.
