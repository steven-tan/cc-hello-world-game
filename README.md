# 3D Space Shooter

A browser-based 3D space shooter game built with [Three.js](https://threejs.org/). Fly your ship, dodge enemies, and blast through waves of alien saucers.

## How to Play

Open `space-shooter.html` in any modern browser — no build step or server required.

### Controls

| Input | Action |
|---|---|
| WASD / Arrow keys | Move ship |
| Mouse | Aim |
| Click / Space | Shoot |
| ESC | Pause |
| Q (while paused) | Quit |
| R (game over) | Restart |

### Gameplay

- Destroy enemy saucers to earn points (100 × current wave).
- Every 8+ kills advances to the next wave — enemies spawn faster and in greater numbers.
- You have 3 lives. Getting hit grants brief invincibility.
- Sound effects are generated with the Web Audio API — no external assets needed.
