# 🚀 Pixel Space Program

A 16-bit style rocket simulator inspired by Kerbal Space Program. Built as a single HTML file — no build step, no dependencies, no nonsense.

![Made with HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![Made with CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![Made with JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- **CRT pixel-art aesthetic** — scanlines, chunky fonts, authentic retro UI
- **Rocket Builder** — click-to-place parts with live TWR/mass stats
- **Quick Launch** — pre-built rocket for instant flight
- **Real-ish physics** — thrust, gravity falloff, atmospheric drag, aerodynamic fins
- **Staging** — drop boosters, deploy parachutes
- **Atmosphere → Space** progression with dynamic sky color
- **Achievements & score** for milestones
- **Minimap** showing your altitude through the atmosphere

## 🎮 Controls

| Key       | Action               |
|-----------|----------------------|
| `SPACE`   | Throttle up          |
| `←` / `→` | Yaw left / right     |
| `↑` / `↓` | Pitch                |
| `Z`       | Stage (drop boosters / deploy chute) |
| `X`       | Toggle SAS (auto-stabilize) |
| `P`       | Pause                |
| `R`       | Reset flight         |

## 🚀 Hosting on GitHub Pages

### Option A: User site (recommended for `username.github.io`)

1. Create a new repository named **`<your-username>.github.io`** (e.g., `octocat.github.io`)
2. Upload `index.html` (and this README if you want) to the root
3. Commit and push
4. Visit `https://<your-username>.github.io` — that's it!

### Option B: Project site (lives at `username.github.io/repo-name`)

1. Create any repo (e.g., `pixel-space-program`)
2. Upload `index.html` to the root
3. Go to **Settings → Pages**
4. Under **Source**, choose `Deploy from a branch`
5. Pick `main` branch, `/ (root)` folder, click **Save**
6. Wait ~30 seconds, then visit `https://<your-username>.github.io/pixel-space-program/`

### Quick command-line setup

```bash
# Create the repo locally
git init
git add index.html README.md
git commit -m "Initial commit: Pixel Space Program"

# Connect to your GitHub repo (replace URL)
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

Then enable Pages in repo Settings as described above.

## 📁 File Structure

```
your-repo/
├── index.html    ← The whole game (single file, ~50KB)
└── README.md     ← This file
```

That's the entire project. No `node_modules`, no build pipeline, no framework lock-in. Just open it.

## 🛠 Customization

Everything lives in `index.html`. Some fun things to tweak:

- **`PARTS` object** — add new rocket components with custom mass/thrust/fuel
- **`makeQuickRocket()`** — change the default rocket layout
- **CSS `:root` variables** — change the color palette (try a Game Boy green theme!)
- **`G` constant** — gravity strength
- **`PLANET_RADIUS`, `ATMO_HEIGHT`, `SPACE_HEIGHT`** — world scale

## 🎯 Tips for First Flight

1. **TWR > 1.2** — your Thrust-to-Weight Ratio must exceed 1.2 to lift off (check the builder)
2. **Hold SPACE** to throttle up gradually
3. **Press X for SAS** to keep the rocket pointed straight
4. **Tilt slightly east (→)** around 1km altitude for a gravity turn
5. **Press Z to drop boosters** when they run dry — saves dead weight
6. **Parachutes deploy automatically** below 1.5km if you're falling fast — or press Z to deploy manually

## 📜 License

MIT — do whatever you want with it.

---

Made with ❤️ and a lot of pixels.
