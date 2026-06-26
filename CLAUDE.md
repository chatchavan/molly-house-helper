## Project

A self-contained web companion for the **Molly House** board game (Wehrlegig Games, 2025).

| File | Purpose |
|------|---------|
| `molly-house-helper.html` | Interactive phase helper — single HTML+JS file, no build step |
| `molly-house-reference.html` | A4 print reference sheet — static HTML, no JS |

Game materials (PDFs) are in `Molly house game/` and are the authoritative source of truth for all rules content.

## Architecture

Both files are self-contained. The helper persists state to `localStorage` (player count, current week, raided houses, current phase). No frameworks, no build pipeline — open directly in a browser.

Key data constants in `molly-house-helper.html`:
- `JOY_THRESHOLD` — Community Survival thresholds per player count (sourced from the board's joy track)
- `DESIRE_MAX`, `HAND_SIZE`, `FEST_ROUNDS`, `FEST_MIN_HAND` — player-count-driven values
- `SUITS` — the four suit/house mappings (Pentacles→Mother Clap's, Fans→Miss Muff's, Hearts→Sukey Bevell's, Cups→Julius Cesar Taylor's)

## Conventions

Build incrementally per spec and confirm each milestone; prefer modular refactors over monolithic rewrites.

All rules content must be sourced from the PDFs in `Molly house game/` — do not invent or infer rules. When adding content, cite the rulebook page in comments or inline quotes.
