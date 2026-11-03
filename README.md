# Dropzone — Local Battle Royale

A single-file, Fortnite-inspired local battle royale game built in vanilla HTML5 Canvas/JavaScript. No build step, no dependencies — just open `index.html` in a browser and play.

## How to run

```bash
# Option 1: open directly
open index.html

# Option 2: serve locally (recommended for audio permissions)
python3 -m http.server 8080 -b 0.0.0.0
# then visit http://localhost:8080
```

## Controls

| Action | Key |
|--------|-----|
| Move | `W A S D` |
| Sprint | `SHIFT` |
| Aim | Mouse |
| Shoot / Swing | Click |
| Weapons | `1` Rifle `2` Shotgun `3` Pickaxe |
| Build mode toggle | `4` |
| Build piece (in build mode) | `1` Wall `2` Floor `3` Ramp |
| Build piece cycle | `Q` / `E` |
| Place build | `F` |
| Rotate ramp / Reload | `R` |

## Gameplay

- **Shoot** bots with the assault rifle or shotgun; pickaxe for melee and destroying builds.
  Hits are instant, so walls and trees will stop bullets — yours and theirs.
- **Build** walls, floors, and ramps for cover (costs wood/brick/metal). Place a ghost preview with `F`.
- **Loot** crates scattered on the map: `AR`/`SG` ammo + materials, `SH` shield, `HP` health.
  Walk over a crate to pick it up.
- **Storm** closes in over time — stay inside the safe circle or take damage (shields soak it first).
- Bots hunt the nearest target, so they fight each other as readily as they fight you —
  step back and let two of them trade shots, then clean up the winner.
- Bots strafe in firefights and retreat toward the circle when the storm catches them.
- Eliminate all 4 bots and survive the storm for **Victory Royale**. You drop in with 50 shield.

## Tips

- `SHIFT` sprinting helps you rotate into the circle, but it also makes you a louder target.
- Build a wall before peeking a bot at range; the wall takes the damage instead of your shields.
- The shotgun shreds at close range, the rifle wins mid-range; the pickaxe also breaks builds fast.

## Files

- `index.html` — complete game (HTML + CSS + JavaScript in one file)
- `LICENSE` — MIT

## Preview

The game is designed to run locally. Serve it with any static file server (e.g. `python3 -m http.server`) and open it in a modern browser. Headphones recommended.
