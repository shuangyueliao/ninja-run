# Ninja Run

An ink-brush wall-jump ninja runner. Single-file HTML5 — no external assets.

Play: you never stop running. Jump gaps, kick up towering walls (kicks are
automatic on wall contact, and you can press jump while sliding on a wall for
an extra push), bounce off swinging paper lanterns, dodge thorns, grab scrolls
(+1) and ring the gong at the end of every level (+50).

- **Story mode** — 10 handcrafted levels, 5 lives, mid-level checkpoint flags.
- **Endless mode** — procedurally stitched segments with guaranteed-reachable exits.

## Controls

| Action | Keyboard | Touch |
|---|---|---|
| Jump / double jump / wall-kick | Space, ↑, W | Tap |
| Fast fall / brake wall slide | ↓, S (hold) | Swipe down (hold) |

## Tech

- Vanilla JS + Canvas + WebAudio (all graphics procedural, all sounds synthesized)
- Domain-guarded portal SDK loader (CrazyGames / GameDistribution events wired; loads nothing elsewhere)
- Best distance & levels cleared saved to localStorage
- Responsive 16:9 canvas, landscape-first, mobile + desktop input

## Run

Serve `index.html` with any static server (e.g. `python3 -m http.server`) and open it.
