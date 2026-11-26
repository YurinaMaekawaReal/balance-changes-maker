# Patch Forge — Balance Changes Maker

A single-file web app for designing balance-change sheets for game characters, with 3D extruded headers and numbers, arrow-patterned columns, and PNG export.

## Use it

Open `index.html` in any modern browser. Everything runs locally; no build step or server needed.

## Features

- **Timeline, single or patch view** — render one character's ticked sessions side by side, one session on its own with big 3D "before → after" numbers, or every character's changes in one patch (sessions with the same date text are grouped).
- **Multiple characters and roles** — one project holds a whole roster; each character can be Strike, Assault, Rapid, Support or Technical, which sets their background color and role icon (icons in `assets/roles/`, also embedded in `index.html`).
- **Verdicts** — Buff, Nerf, Rework and Adjust, each with its own color and arrow pattern (up, down, circular, two-way).
- **Stats and notes** — per-level stat tables colored automatically (set "lower is better" for things like reload time), or free-text notes.
- **Skill images** — click or drop an image onto each ability; empty transparent edges are trimmed automatically, with a global and per-image size; optionally hide the name.
- **7 presets** — Neon Arena, Classic Panels, Holo Chrome, Comic Burst, Esports Minimal, Tactical Ops, Royal Gold; every option is editable afterwards.
- **3D type controls** — depth, angle, outline, glow, face finish, plus rotation / slant / turn for the big numbers.
- **Export** — PNG at 1×–4×; save and load the whole project as `.json`. Work autosaves in the browser.
