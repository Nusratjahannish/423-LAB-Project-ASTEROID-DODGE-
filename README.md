# 423-LAB-Project-ASTEROID-DODGE-
# 🚀 Space Arena 3D (PyOpenGL Game)

A 3D space survival/shooter built with **Python + PyOpenGL + GLUT**.  
Fly your neon spaceship, dodge asteroids and blackholes, collect bonuses, and survive as long as possible.  

---

## 🎮 Features

- **Game States & Flow**
  - Menu → Instructions → Gameplay
  - Pause/Resume, Game Over & Restart

- **Difficulty System**
  - Easy / Medium / Hard  
  - Hard mode adds giant/splitting asteroids and tougher blackholes

- **3D Camera**
  - Orbit mode with height controls (arrow keys)

- **Spaceship**
  - Pulsing neon-styled model with black outline
  - Speed control (`-`/`=`) and bounds clamping
  - Cheat mode: auto-aim & auto-fire with glowing outline

- **Enemies & Hazards**
  - Asteroids: normal, giant, and splitting (Hard mode only)
  - Blackholes: chase the ship, apply slow & drain lives

- **Pickups**
  - Bonus spheres (+3 score)
  - Stasis crystal: freezes world, spawns collectible orbs

- **Weapons & Effects**
  - Bullets with TTL and pulsing visuals
  - Particle blast explosions
  - Floating bonus text projected into the world

- **HUD & Overlay**
  - Lives, score, speed, cheat flag
  - Alerts for slow/stasis/game over
  - Gradient sky, starfield background, neon UI frame

---

## ⌨️ Controls

### Movement
- `A` / `D` → Move Up / Down  
- `L` / `T` → Move Left / Right  
- `W` / `S` → Move Forward / Backward (Z-axis)  
- `-` / `=` → Decrease / Increase speed  

### Gameplay
- `SPACE` → Fire bullet (disabled during stasis)  
- `C` → Toggle cheat mode (auto-aim/autofire)  
- `P` → Pause / Resume  
- `R` → Return to menu  
- `ESC` → Quit  

### Camera
- `Arrow Keys` → Adjust height (orbit mode)  

### Menu
- `1` / `E` → Easy  
- `2` / `M` → Medium  
- `3` / `H` → Hard  
- `ENTER` → Advance (Menu → Instructions → Start)  

