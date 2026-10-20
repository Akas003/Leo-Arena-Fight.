# 🔥 Leo: Arena Fight

A single-file browser brawler inspired by the Tamil film *Leo*. Fight through 50 enemies in 7 waves, then take down the boss with a final shot.

▶️ **Play now:** `https://YOUR-USERNAME.github.io/YOUR-REPO/`
*(replace with your own link after enabling GitHub Pages)*

---

## 🎮 Gameplay

- **50 enemies in 7 waves** (4, 5, 6, 7, 8, 9, 11), getting faster each wave
- **7 enemy types:** basic goon, knife guy, bat guy, pipe guy, tanker, ranged shooter, leather guy
- **Enemy health:** 5–10% of the hero's health bar
- **Hero health:** a big 300 HP bar
- **Knife:** 15 seconds of heavy slashes. Once it runs out, take down 3 enemies to recharge it
- **Punch combo:** the 3rd hit in a row is a heavy hit
- **Boss:** appears after enemy 50, with half the hero's health bar
- **Finale:** a gun-shot cutscene ends the game with *"LEO… LEO… LEO… LEOOOOO…!!"*

## 🕹️ Controls

| Action | Touch | Keyboard |
|---|---|---|
| Move | On-screen D-pad | Arrow keys / WASD |
| Punch | 👊 button | Space or J |
| Knife on/off | 🔪 button | K |
| Start / retry | Tap 👊 | Space |

## ✨ Features

- 2.5D arena with a scrolling camera and a faster-moving foreground layer for depth
- Depth sorting and sprite scaling as fighters move up and down the floor
- Pixel-art sprites for the hero, enemies, and boss
- Hit-stop, screen shake, sparks, and sound effects built with the Web Audio API
- Voice shout in the finale using the browser's speech synthesis
- Mobile-friendly touch controls
- Best score saved in the browser

## 📁 Project structure

```
index.html   ← the entire game (code and images embedded)
README.md
```

No build step, no dependencies, no server needed.

## 🚀 Run it

**Locally:** download `index.html` and open it in any modern browser.

**Host it free with GitHub Pages:**
1. Create a new public repository.
2. Upload `index.html` and `README.md`.
3. Go to **Settings → Pages**, choose the `main` branch and `/ (root)`, then **Save**.
4. Your game goes live at `https://YOUR-USERNAME.github.io/YOUR-REPO/` after a minute or two.

## 🛠️ Tech

Plain HTML, CSS, and JavaScript on a single `<canvas>`. Sprites are packed into one embedded atlas, and the camera, AI, combat, and waves are all in the same file.

## 🗺️ Ideas for later

- Separate animation frames for each enemy type
- Landscape layout with a joystick
- Health pickups and weapon drops
- Boss phases
- Music and a longer arena

## ⚠️ Disclaimer

This is an unofficial, non-commercial fan project made for fun. It is not affiliated with or endorsed by the makers of the film *Leo*. All characters and film references belong to their respective owners. The sprite and background art was supplied by the project owner; replace it with your own or licensed art before using this game commercially.

## 📄 License

Code: MIT License (add a `LICENSE` file if you want to share the code openly).
Art and character likenesses: not covered by the code license.
.
