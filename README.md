# ArchSpatial Studio Rig v1.0 (Blender Python Utility)
**1-Click Architectural 3-Point Lighting Generator for Spatial Design, Product Rendering & VisionOS LookDev.**

![ArchSpatial 3-Point Rig Thumbnail](./thumbnail.png)

## Why This Exists
Setting up physically accurate architectural lighting in 3D viewports takes hours of manual tweaking. Drawn from real-world NYC flagship showroom lighting design, this lightweight Python script (`ArchSpatial_3Point_Rig.py`) builds a production-ready **2.5 : 1 Contrast Ratio 3-Point Studio Rig** with auto-tracking camera and focus targets in **1 second**.

---

## Physical Lighting Specs (Kelvin & Ratio Tokens)
| Light Node | Color Temp | Energy / Size | Spatial & Showroom Role |
| :--- | :--- | :--- | :--- |
| **01_Key_Light** | **3500K** (Gallery Neutral) | `250W` / `2.0m` | Primary directional shaping & Z-depth shadow casting |
| **02_Fill_Light** | **4000K** (Crisp Daylight) | `100W` / `3.2m` | Softens shadow density at a **2.5 : 1 ratio** for UI/texture legibility |
| **03_Rim_Light** | **2700K** (Warm Lounge) | `180W` / `1.2m` | Grazing edge specular highlight to separate silhouettes from background |
| **00_Target_Focus** | Auto-Track Controller | Empty Sphere | Move this single node (`G` key) and all 3 lights + 50mm eye-level camera follow automatically |

---

## How to Use in 30 Seconds (Zero 3D Experience Needed)
1. Download **`ArchSpatial_3Point_Rig.py`** from this repository.
2. Open **Blender** → Click the **`Scripting`** tab on the top menu bar.
3. Click **`Open`** → Select `ArchSpatial_3Point_Rig.py` → Click the **`▶ (Run Script)`** button.
4. Switch your 3D Viewport shading (top right 4th sphere icon) to **`Rendered`**.
5. Select `00_Light_Target_Focus (Move_Me)` and press **`G`** to aim all lights simultaneously!

---

## Free Spatial Design Systems & Weekly Dispatch
This utility is **100% Free & Open-Source** (MIT License), part of the **ArchSpatial** design system bridging physical architecture and spatial computing (VisionOS / XR).

* **Figma Community UI Kit (Asset #1):** Search `@archspatial` on Figma Community
* **Join the Free Newsletter (ArchSpatial Dispatch):** (https://substack.com/@archspatial)
  *(Get weekly spatial UI tokens, 3D Python automation scripts, and architectural LookDev guides delivered to your inbox for free.)*
