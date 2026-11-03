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
| Build piece cycle | `Q` / `E` |
| Place build | `F` |
| Rotate ramp / Reload | `R` |

## Gameplay

- **Shoot** bots with the assault rifle or shotgun; pickaxe for melee and destroying builds.
- **Build** walls, floors, and ramps for cover (costs wood/brick/metal). Place a ghost preview with `F`.
- **Loot** crates scattered on the map for ammo and materials.
- **Storm** closes in over time — stay inside the safe circle or take damage.
- Eliminate all 4 bots and survive the storm for **Victory Royale**.

## Files

- `index.html` — complete game (HTML + CSS + JavaScript in one file)
- `LICENSE` — MIT

## Preview

The game is designed to run locally. Serve it with any static file server (e.g. `python3 -m http.server`) and open it in a modern browser. Headphones recommended.
