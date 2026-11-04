# Ninja Run — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

An ink-brush ninja runner where walls are your ladder. Auto-run, leap gaps,
kick up towering walls, bounce off glowing paper lanterns, dodge thorns, grab
scrolls and ring the gong. 10 handcrafted levels + endless mode.

(Length check: 229 chars — see trimmed variant below for 200-char limits)

Trimmed variant (≤200 chars):

Ink-brush ninja runner. Walls are your ladder: auto-run, leap gaps, kick up
towers, bounce on lanterns, dodge thorns, ring the gong. 10 levels + endless.

## Details

- Genre: Action / Runner / Platformer
- Controls: Space / Tap = jump, double jump & wall-kick (wall kicks trigger
  automatically on contact). ↓ / swipe down = fast fall & wall-slide brake.
- Features:
  - Wall-jump physics: running into a wall chains up to 3 automatic kicks per
    landing; sliding on a wall slows your fall; holding down breaks the slide
    into a fast fall.
  - 10 handcrafted levels with progressive mechanics (gaps, spikes, tall walls,
    swinging lantern bounce, checkpoint flags, gong finish +50).
  - Endless mode built from a segment template library — every segment exit
    matches the next segment entrance, verified reachable by automated playtest.
  - Scoring: scrolls +1, gong +50; farthest distance and levels cleared saved
    locally.
  - 5 lives in story mode with mid-level checkpoints; death respawns at the
    last flag.
- Visuals: Japanese ink-wash style — paper background, faded-ink parallax
  mountains, bamboo groves, red-scarf ninja with motion afterimages, wall-kick
  dust, warm lantern glow. All procedural canvas drawing.
- Audio: synthesized with WebAudio (jump, wall-kick, collect, lantern bounce,
  gong, death). No audio files.
- Tech: single-file HTML5, vanilla JavaScript, zero external assets, works
  offline once loaded. No analytics, no external links.

## Tags

ninja, runner, platformer, action, arcade, wall-jump, ink, single-file, endless

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (16:9 canvas letterboxed, landscape-first)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720) — to be captured from gameplay
- [ ] Screenshots — to be captured from gameplay

## GameDistribution
- Upload ninja-run-gd.zip (contains index.html only)
- Entry file: index.html; the GD SDK loader activates automatically on
  gamedistribution / gd.games domains.

## itch.io
- Upload ninja-run-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport 960×540, kind: html
- Pricing: $0 (donations optional)
