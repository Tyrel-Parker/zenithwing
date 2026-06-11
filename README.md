# ZenithWing

A mobile-first vertical scrolling arcade shooter playable in any browser. Tilt your phone to fly, dodge enemy fire, and collect upgrades as you push deeper into enemy airspace.

**Play:** [zenithwing.tyrelparker.dev](https://zenithwing.tyrelparker.dev)

## Controls

| Mode | How |
|------|-----|
| Tilt | Tilt phone left/right and forward/back to steer |
| Touch | Drag your finger — the plane follows |
| Keys | WASD or arrow keys (desktop) |

Switch modes with the button at the top. On iOS, tilt requires a permission tap.

## Gameplay

- Your plane **auto-fires** — focus on positioning and collecting drops
- Three enemy types with escalating difficulty each wave
- Enemies drop power-ups when destroyed

### Power-ups

| Drop | Effect |
|------|--------|
| **P** | Increase fire spread (up to 5-way) |
| **S** | Shield — absorbs one hit |
| **R** | Rapid fire for 8 seconds |
| **B** | Bomb — clears all enemies on screen |

Getting hit drops your power level by one. Collecting a shield before a hit keeps your power level intact.

## Stack

Single `index.html` — no build step, no dependencies. HTML5 Canvas 2D, vanilla JS, `Press Start 2P` font from Google Fonts. High scores stored in `localStorage`.
