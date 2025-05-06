# clothes_generator
---

## 🧵 Cloth Simulation & Export Guide

### 📥 Importing Cloth Mesh
- Cloth mesh should be **a single, unioned, and simple** geometry.
- To import a new cloth mesh, click **"Import Cloth"** in the **Cloth Processor**.

---

### 🧪 Presimulation Setup
- Before running presimulation:
  - Delete the `cached_clothes` files from the HIP file directory.
- Click **"Presim Clothes"** to begin cloth presimulation.

---

### ⚙️ Simulation & Optimization

> **Note:** The **Simulation** and **Optimize** panels apply to **cable simulation only**.

#### Sim Cable or Cloth
- To simulate **cable**: ✅ Tick `Sim Cable or Cloth` in the **Main Cable** panel.
- To simulate **cloth**: ❌ Untick `Sim Cable or Cloth`.

#### Cloth Simulation Steps
- To preview the pre-simulated cloth arrangement:
  - Set a seed in the **Sim Clothes** panel.
  - ✅ Tick `PreviewSim`.
- To simulate cloth:
  - Set **Subcable** to `0`.
  - Click **"Sim Clothes"** in the **Sim Clothes** panel.
- To view the cloth simulation:
  - Set the timeline frame to match the frame in **Export Frame** (from **Sim Clothes** panel).
  - ✅ Tick `ViewSim`.

---

### 🎬 Exporting Cloth

- Use the **Test** button to jump to the frame set in **Export Frame**.
- To find your preferred simulation result:
  - Scrub through the frame strip manually.
- Once satisfied:
  - Input the chosen frame into **Final Frame** under **Output Setting**.
  - Click **"Export FBX"** to export the result.

---
