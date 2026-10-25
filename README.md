# Hanoi Roadster Rocket 

English version of [teslaroadstertest](https://github.com/toilalode/teslaroadstertest).

Drive a Tesla Roadster (SpaceX package) through Hanoi: 10 km, 15 minutes, intersections, Supercharger stations, flying, dodge rolls and wall grip.

Play at: https://toilalode.github.io/teslaroadstertesteng/

## Structure

| File | Role |
| --- | --- |
| `index.html` | Page shell, loads Three.js r128 from cdnjs and the modules in `js/` in order |
| `style.css` | HUD, popup and touch-button styling |
| `js/config.js` | Route constants, helper functions, default settings |
| `js/scene.js` | Renderer, scene, lighting, mesh helpers |
| `js/vehicles.js` | Traffic vehicles and the SpaceX Tesla Roadster model |
| `js/city.js` | Road, buildings, intersections, charging stations, roadworks, office |
| `js/state.js` | State, traffic spawning, collisions, police, skills |
| `js/autopilot.js` | Autopilot (toggle with T): lane keeping, traffic avoidance, red lights, auto-charging every 2000 m, auto-turn into the office |
| `js/physics.js` | Physics, collisions, traffic |
| `js/hud.js` | Camera, HUD, minimap |
| `js/screens.js` | Menu, Settings, end screen |
| `js/input.js` | Keyboard, touch, mouse |
| `js/main.js` | Main loop |
| `sw.js`, `manifest.json`, `icon.svg` | PWA, offline support |
| `.github/workflows/pages.yml` | GitHub Pages deployment |

## Enable GitHub Pages

Settings > Pages > Build and deployment > Source: **GitHub Actions**, then re-run the workflow.
