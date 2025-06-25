## 🎨 Dino Color Game (WASM Edition)

An interactive color-matching game built in C, rendered via WebAssembly, and playable directly in the browser. The player adjusts RGB sliders to match a target circle color.

![Screenshot from 2025-06-25 14-42-04](https://github.com/user-attachments/assets/876582ea-13a9-48d6-a841-0010a178d07e)

### 🌐 [Play Now](https://42-course.github.io/dino_game/demo.html)

---

### 🕹️ Gameplay

**Objective:**
Match the inner circle's color to the outer circle using RGB sliders.

**Rules (displayed in-game):**

* Use keys to adjust red, green, and blue values.
* Try to make both circles visually match.
* Submit your guess and see if you're right!

---

### 🧱 Built With

* **C** – core game logic and rendering
* **Emscripten** – compiles C code to WebAssembly
* **HTML/CSS** – styled interface and deployment layer
* **WebGL (via MLX-like API)** – graphical rendering backend

---

### 📦 Folder Structure

```
├── demo.html       # Full game HTML page
├── embed.html      # Minimal canvas-only version for embedding
├── demo.js         # Emscripten JS glue code
├── demo.wasm       # Compiled WebAssembly binary
├── demo.data       # (optional) game assets
├── README.md
```

---

### 📎 Embedding

Use this `<iframe>` to embed the game anywhere:

```html
<iframe 
  src="https://42-course.github.io/dino_game/embed.html"
  width="800" 
  height="600" 
  style="border: none; border-radius: 10px; box-shadow: 0 0 20px rgba(0,255,180,0.3);"
  loading="lazy">
</iframe>
```

---


### 📃 License

Just don't take the credit for creating the game, if you mention me it's awesome!

---
