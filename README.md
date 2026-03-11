# AETHERIUM: The Hollow War

A browser-based 3D first-person shooter with sci-fi horror themes. Built entirely in HTML5, Three.js, and JavaScript — no downloads, no installs, just open and play.

## 🎮 Play Now

**Live Demo:** https://tektonxyz.github.io/aetherium-fps/

Open in any modern browser (Chrome, Firefox, Edge recommended). Click "Initialize Mission" to start.

## 📖 The Story

**Year 2187.** Location: Aetherium Station, orbiting Proxima Centauri b.

The station was humanity's greatest achievement — a self-sustaining megastructure housing 2 million souls, powered by experimental quantum reactors. Then **the Hollow** came.

They are not aliens. Not machines. They are *absence* given form — entities that phase through solid matter, drain life force on contact, and reproduce by converting biomass into more Hollow. The station's AI core malfunctioned. Life support is failing. 98% of the population is either dead or converted.

You are **Subject-7**, a cybernetically enhanced operative from the Aegis Program. Your neural implants allow you to perceive the Hollow's phase-shifted forms. Your mission: Survive wave after wave of Hollow attacks, rack up the highest score possible, and hold out as long as you can.

Good luck, operative.

## 🕹️ Controls

| Action | Key |
|--------|-----|
| Move | W A S D |
| Look | Mouse |
| Shoot | Left Click |
| Aim Down Sights | Right Click |
| Reload | R |
| Switch Weapon 1 | 1 |
| Switch Weapon 2 | 2 |
| Switch Weapon 3 | 3 |
| Sprint | Shift |
| Pause | Escape |

**Note:** The game captures your mouse cursor for FPS controls. Press Escape to release the cursor and pause.

## ⚡ Features

- **Full 3D FPS Engine** — Smooth mouse look, WASD movement, weapon recoil
- **Weapon System** — AEGIS-7 Rifle with muzzle flash, bullet tracers, and reload mechanics
- **Enemy AI** — Four distinct enemy types:
  - **Drone** — Basic fast attacker (50 HP)
  - **Stalker** — Agile hunter (80 HP)
  - **Tank** — Slow but devastating (200 HP)
  - **Phantom** — Fast glass cannon (40 HP)
- **Wave System** — Enemies spawn in increasingly difficult waves
- **Visual Effects** — Dynamic lighting, particle explosions, energy tendrils
- **Sci-Fi Aesthetic** — Cyberpunk-inspired HUD, neon accents, dark atmosphere

## 🎯 How to Play

1. Click "Initialize Mission" to start
2. Look around with your mouse
3. Enemies will spawn around you in waves
4. Shoot the glowing cyan/purple entities before they reach you
5. Don't let your health hit zero
6. Survive as many waves as possible and rack up score

## 🛠️ Technical Details

- **Engine:** Three.js (3D rendering)
- **Physics:** Custom collision detection
- **Input:** Pointer Lock API for FPS controls
- **Audio:** Web Audio API (placeholder for future updates)
- **Size:** ~54KB single HTML file
- **No external assets** — everything generated procedurally

## 📝 Development Notes

Built as a demonstration of what's possible with modern web technologies. All graphics, textures, and models are generated in real-time using JavaScript — no image files, no model downloads.

### Performance Tips

- Use Chrome or Firefox for best performance
- Close other browser tabs
- Lower your monitor resolution if experiencing lag
- The game targets 60 FPS on modern hardware

## 🐛 Known Issues

- Safari may have pointer lock issues
- Mobile devices not supported (requires keyboard + mouse)
- Some older GPUs may struggle with the lighting effects

## 🔮 Future Updates

- [ ] Additional weapons (shotgun, sniper, plasma rifle)
- [ ] Boss battles every 5 waves
- [ ] Power-ups and ammo drops
- [ ] Multiple levels/maps
- [ ] Multiplayer support (WebRTC)
- [ ] Sound effects and music
- [ ] Save/load high scores

## 📄 License

MIT — Feel free to fork, modify, and distribute. Credit appreciated but not required.

## 🙏 Credits

Built by TektonXYZ using Three.js and pure JavaScript. Inspired by classic arena shooters like Quake and Doom, with a cyberpunk horror twist.

---

**Deploy Status:** [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://tektonxyz.github.io/aetherium-fps/)
