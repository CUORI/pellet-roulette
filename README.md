# PELLET ROULETTE

Browser-based FPS roguelite prototype. Live build: https://cuori.github.io/pellet-roulette/

## v0.4: Pellet pool prototype

- FPS movement: WASD, mouse, Space jump, hold Shift sprint, double-tap Shift tactical sprint.
- Shotgun: left click to shoot six independently drawn pellets; R for per-shell reload; shooting interrupts reload.
- Build editor: B; preset builds: 1 balanced, 2 fire, 3 shock.
- Pellet pool weights: normal 12 direct damage, fire 6 plus damage over time, shock 7 plus nearby target chain damage. Each pellet draw is **with replacement** from the pool.
- Cover blocks pellets; moving targets respawn. HUD shows last draw, hit and kill statistics.
- Audio diagnostic on pause/start screen.

## Playtest checklist

1. Movement: normal jump vs air strafe, sprint and tactical sprint, speed retention and obstacle collisions.
2. Gunplay: recoil and muzzle flash, hit confirmation, shooting at cover, target respawn, shooting during reload.
3. Builds: B opens editor, changes take effect after Apply; test presets 1/2/3; ensure draw icons change with pool weights.
4. Effects: fire damage persists briefly; shock affects nearby targets; confirm no damage through cover (including chain effect, currently simplified).
5. Browser: mouse pointer lock, audio after user click, FPS/performance, reload after page refresh.

## Known limitations

This is a gameplay prototype, not a finished game. Chain damage is radius-based and does not check line-of-sight. No enemy AI, health, permanent progression, shell rules, or gun upgrade system yet. Visuals and synthesized audio are placeholders. No full browser QA has been performed.

## Version history

- v0.1: first FPS movement and shotgun test arena.
- v0.2: independent GitHub Pages deployment, audio diagnostics.
- v0.3: combat feedback, cover blocking, hit/kill counters.
- v0.4: pellet pool editor, random six-pellet draw, fire DOT, shock chain, build presets.
