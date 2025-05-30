# 🐍 Basic Snake HTML Game

This is a simple implementation of the classic Snake game using only HTML5, CSS, and JavaScript. It's designed to run in the browser and does not require any external libraries or frameworks.

---

## 🎮 Features

- Classic snake movement using arrow keys.
- Apples randomly spawn on the grid.
- Snake grows longer each time it eats an apple.
- Game restarts when the snake runs into itself.
- Canvas-based rendering for smooth performance.

---
## 🎮 Controls

- ⬅️ **Left Arrow**: Move Left  
- ⬆️ **Up Arrow**: Move Up  
- ➡️ **Right Arrow**: Move Right  
- ⬇️ **Down Arrow**: Move Down  

> ⚠️ The snake cannot directly reverse into itself.

---

## 🧠 Game Logic

- **Canvas size**: `400x400`
- **Grid size**: `16x16`
- **Frame rate**: Snake moves every few frames (approximately 15 FPS)
- **Apple behavior**: Apples spawn randomly on the grid
- **Collision**: Game resets when the snake collides with itself
