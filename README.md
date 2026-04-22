# 🌍 Procedural World Builder

An interactive, browser-based procedural terrain editor and explorer built with **JavaScript** and **Three.js**.

Generate infinite-style worlds, sculpt terrain in real time, paint biomes, and jump into a first-person mode to explore your creation.

---

## ✨ Features

### 🗺️ Procedural World Generation

- Seed-based terrain generation using noise functions  
- Heightmap + moisture simulation  
- Automatic biome classification:
  - 🌊 Ocean  
  - 🏖️ Beach  
  - 🌾 Plains  
  - 🌲 Forest  
  - 🏜️ Desert  
  - ❄️ Tundra  
  - ⛰️ Mountain  
  - 🧊 Snow Cap  

---

### 🛠️ Real-Time Terrain Editing

- Raise / Lower terrain  
- Smooth and Flatten tools  
- Adjustable brush size  
- Instant visual feedback  

---

### 🎨 Biome Painting

- Override generated biomes with manual painting  
- Erase overrides to revert to procedural generation  
- Colour-coded biome system  

---

### 🧭 Interactive Map UI

- Pan and zoom across the world  
- Minimap with viewport indicator  
- Live coordinate tracking  

**Adjustable world parameters:**
- 🌳 Tree density  
- 🌿 Clutter density  
- 🚫 Collision toggle  

---

### 🧍 First-Person Exploration Mode

- Drop into the world from the map  
- WASD movement + mouse look  
- Pointer lock controls  
- Dynamic terrain rendering with lighting and fog  

---

### 🌱 Procedural Environment

- Chunk-based terrain loading  
- Dynamic object placement (trees, clutter)  
- Performance-optimised rendering  

---

## 🎮 Controls

### 🗺️ Map Mode

| Action            | Control                          |
|------------------|----------------------------------|
| Pan              | Middle mouse OR `Space + Drag`   |
| Zoom             | Mouse wheel                      |
| Paint terrain    | Left click                       |
| Change tool      | Toolbar                          |
| Adjust brush     | Slider                           |

---

### 🧍 Explore Mode

| Action        | Control              |
|---------------|----------------------|
| Move          | `W A S D`            |
| Sprint        | `Shift`              |
| Look          | Mouse                |
| Lock cursor   | Click                |
| Exit          | "Back to Map" button |

---

## 🧠 How It Works

### 🌍 Terrain Generation

- Uses **Simplex Noise** + **FBM (Fractal Brownian Motion)**  
- Applies continental falloff for island-like worlds  
- Combines:
  - Heightmap  
  - Moisture map  

➡️ Used together to derive biome distribution  

---

### 🎮 Rendering

- 🖼️ 2D Canvas for map view  
- 🌐 Three.js for 3D exploration  
- ⚡ Chunk-based system for performance  

---

### 🌿 Biome System

Biomes are derived from:

- Elevation (height)  
- Moisture  
- Latitude  

Manual overrides allow fine control when needed.

---

## 🚀 Usage
Visit https://explorableworldgenerator.vercel.app/
