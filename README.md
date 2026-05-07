# 🚀💖 Big Alien Bazoongas

> *A 16-bit interstellar romance.*

Build a rocket. Escape Earth. Reach **Planet Bazoon** at 8km altitude where the alien greeters are waiting to welcome you to their world. A goofy B-movie pulp space sim, single HTML file, no build step.

![Made with HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![Made with CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![Made with JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- **Mission objective** — reach Planet Bazoon (8km up) for a victory ending
- **Pixel-art alien greeters** waiting on the surface, waving hello, with hearts and a "WELCOME!" sign
- **Rocket Builder** — click-to-place parts with live TWR/mass stats
- **Quick Launch** — pre-built rocket for instant flight
- **Real-ish physics** — thrust, gravity falloff, atmospheric drag, aerodynamic fins
- **Staging** — drop boosters, deploy parachutes
- **Atmosphere → Space → Bazoon** progression with a sky that shifts from blue to purple to deep space pink
- **CRT pixel-art aesthetic** — scanlines, chunky fonts, hot-pink retro UI
- **Achievements & Love score** for milestones

## 🎮 Controls

| Key       | Action               |
|-----------|----------------------|
| `SPACE`   | Throttle up          |
| `←` / `→` | Yaw left / right     |
| `Z`       | Stage (drop boosters / deploy chute) |
| `X`       | Toggle SAS (auto-stabilize) |
| `P`       | Pause                |
| `R`       | Reset flight         |

## 🎯 Mission

1. Build (or use the quick-launch) rocket
2. Hold SPACE to throttle, hit X for SAS to keep pointing up
3. Around 1km, drop your boosters with Z
4. Climb past the atmosphere (2.2km) into space
5. Keep climbing — Planet Bazoon appears around 4km
6. **Reach 8km altitude and dock with Planet Bazoon for the win**

## 🚀 Hosting on GitHub Pages

### Option A: User site at `username.github.io`

1. Create a repo named **`<your-username>.github.io`** (e.g. `octocat.github.io`)
2. Upload `index.html` to the root
3. Commit and push
4. Visit `https://<your-username>.github.io`

### Option B: Project site at `username.github.io/repo-name`

1. Create any repo (e.g. `big-alien-bazoongas`)
2. Upload `index.html` to the root
3. Go to **Settings → Pages**
4. Source: `Deploy from a branch` → `main` / `(root)` → Save
5. Visit `https://<your-username>.github.io/big-alien-bazoongas/`

### Quick command-line setup

```bash
git init
git add index.html README.md .nojekyll
git commit -m "Launch 🚀💖"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

## 🛠 Customization

Everything's in `index.html`. Some fun knobs:

- **`PARTS` object** — add new rocket components
- **`BAZOON_HEIGHT`** — how far away Planet Bazoon is (default 8000)
- **`drawAlien()` function** — change the alien designs (skin colors, hair, antennae, accessories)
- **`triggerVictory()`** — customize the victory text and effects
- **CSS `:root` variables** — change the whole color palette

## 📜 License

MIT — do whatever you want with it.

---

Made with ❤️ across the cosmos.
