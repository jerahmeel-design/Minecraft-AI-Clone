# ⛏ Minecraft Clone

**A complete Minecraft-style voxel game in a single HTML file.** Random worlds, mining, crafting, caves, day/night, mobs, torches — playable on desktop *and* mobile, right in your browser. No install, no build step.

🎮 **Play it here:** `https://minecraftclone.com`

<!-- Replace the line above with your live GitHub Pages URL, and add a screenshot here! -->

---

## ✨ Features

### 🌍 World
- **Infinite variety** — every load generates a brand-new world from a random seed
- **Shareable seeds** — play any world again with `?seed=123456` in the URL
- Caves carved by 3D noise — explore them!
- **Ores** underground: coal, iron, and gold (deepest)
- Snowy mountain peaks, beaches, lakes, trees, flowers & tall grass
- Animated water with waves, depth colors, and full swimming + diving

### 🎮 Gameplay
- **Hold to mine** — cracks spread across the block, then it bursts into particles
- **Survival inventory** — starts empty; mine blocks to collect them (stacks up to 64)
- **Crafting menu** (press `E`):

| Ingredients | Output |
|---|---|
| 1 Wood | 4 Planks |
| 2 Stone | 4 Cobble |
| 2 Sand + 1 Dirt | 4 Brick |
| 2 Dirt + 1 Leaves | 1 Grass |
| 4 Sand | 1 Glass |
| 1 Wood + 1 Coal Ore | 2 Torches |
| 1 Gold Ore + 1 Coal Ore | 1 Glowstone |

- **Health & survival** — 10 hearts, fall damage, drowning (watch the bubbles!), auto-regen, respawn on death
- **Day/night cycle** — moving sun & moon, orange sunsets, stars, real darkness (bring torches!)
- **Torches & glowstone** — placeable flickering lights for caves and night builds
- **Mobs** — sheep, pigs, and cows wander the world with animated legs
- **Auto-save** — world edits, inventory, position, and time persist in your browser

### 🔊 Tech
- Procedural sound effects (Web Audio — dig, place, splash, footsteps, damage, craft chime)
- Built with **Three.js** — one `index.html` file, nothing to build

---

## 🕹 Controls

### Desktop
| Input | Action |
|---|---|
| `WASD` | Move |
| `Space` | Jump / swim up |
| `Shift` | Sprint |
| **Left click** | Place block |
| **Right click** (hold) | Mine block |
| `E` | Crafting menu |
| `1–9` / scroll | Select slot |
| `Esc` | Release mouse |

### Mobile / Tablet
| Input | Action |
|---|---|
| Joystick (bottom-left) | Move |
| Drag the screen | Look around |
| ↑ button | Jump / swim up |
| + button | Place block |
| × button (hold) | Mine block |
| Tap hotbar | Select slot |
| CRAFT button | Crafting menu |

> 📱 Tip: landscape mode works best.


---

## 💡 Tips for Players

- Punch trees first → craft planks, then mine coal for **torches** before exploring caves at night.
- Gold ore hides deep — dig down and light your way.
- Found a cool world? Copy the seed from the start screen and share it via `?seed=...`
- Progress auto-saves every few seconds. Want a fresh start? Use the **New World** button on the title screen.

---

## 🛠 Built With

- [Three.js](https://threejs.org/) (r128, loaded from CDN)
- Vanilla JavaScript, CSS, Web Audio API
- localStorage for saves

## 📄 License

MIT — do whatever you want, have fun!

---

*Inspired by Minecraft. Not affiliated with Mojang.*
