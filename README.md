# Renovation Simulator — Unreal Engine 5 🎮🛠️

[YouTube Preview ▶️](https://youtu.be/_9fxAEfgmrA)

---

![Preview Image](https://media.fab.com/image_previews/gallery_images/c745f6f9-ed0e-4ac6-b08f-d7784194cdce/43aad675-916e-4329-961d-0a99ca9c4ed0.jpg)

Hello! 👋 This is my personal project — **Renovation Simulator**, built with Unreal Engine 5 and entirely powered by Blueprints logic. This repository showcases renovation mechanics, object interaction, and a player progression system.

---

# ✨ Key Features

* ⏰ **Day/Night cycle with clock**
* 📱 **Interactive tablet** for interior management
* 💰 **Monetary system** (buy/sell)
* 🗑️ **Garbage collection**
* 🧽 **Dirt cleaning**
* 🎨 **Painting walls, doors, pillars, and ceilings** (both sides)
* 🧱 **Fence repair**
* 🎡 **Selection wheel**
* 🪙 **Sell items**
* 📈 **Leveling and XP system**
* ✨ **Interaction system with outline**
* 🧩 **Structure meshes**: walls, doors, stairs, pillars
* ⏸️ **Pause menu**
* 🔢 **FPS counter, crosshair**

---

# 🔄 Latest Updates

* **September 2024** — Added support for Unreal Engine 5.3 ✅
* **May 2024** — Added support for Unreal Engine 5.4 ✅
* **July 2024** — Fixed an issue with quickly picking up trash 🐞

> All changes are reflected in the commit history and release notes.

---

# 🛠️ Technical Details (Blueprints)

## 🌓 Day/Night Cycle Logic

**Initialization (Event BeginPlay):**

* Get the player character and cast to `BP_FirstPersonCharacter`.
* Store the reference in a variable `Player`.

**Day/Night Cycle (Event Tick):**

1. `Event Tick` provides `Delta Seconds`.
2. Multiply `Delta Seconds` by `Day Length` (float) — controls time speed.
3. Pass the result to the `Clock` function (updates internal time) and rotate `Directional Light` using `Add Actor Local Rotation`.
4. Get `Actor Rotation` and check `Pitch`:

   * If between **0–100**, it’s considered **night**.
5. Based on the `Night Time` flag, call `NightLighting` or `DayLighting`.

![Day/Night Blueprint Logic](https://sun9-31.userapi.com/s/v1/if2/r3k_4QrB-AH6gpEroxdzXV6VjmW6CptQn6WcR1aokgrS5fTHXOrW8wtWpRSC_sFpWPMSGBXyPlV2808J8vrSwuvC.jpg?quality=95\&as=32x16,48x24,72x36,108x54,160x80,240x119,360x179,480x239,540x269,640x318,720x358,1080x537,1280x637,1440x716,2048x1019\&from=bu\&cs=2048x0)

---

## 📱 Interactive Tablet

* Open/close with **TAB**.
* Menu has 4 main categories for interior customization:

  * **🎨 PAINT** — choose wall color (12 available colors).
  * **🧱 WALLS** — decorative panels (currently red & white pattern).
  * **🪵 FLOORS** — floor texture (wood — brown).
  * **🏠 CEILINGS** — ceiling painting (default: pastel white).
* **Back** button available in every section.

![Tablet Menu](https://sun9-85.userapi.com/s/v1/if2/7x0g0cGxwInAeFSot3kS-24wcGumIWuUziFhJJc3c4wFv44KUZvetKHnnJxdcRHR1Zd4bAnG2H75gMbMl6d2iLIH.jpg?quality=95\&as=32x20,48x30,72x46,108x69,160x102,240x152,360x229,480x305,540x343,640x406,720x457,940x597\&from=bu\&cs=940x0)

### 🎨 Available Colors (PAINT)

* White ⚪
* Red 🔴
* Light Blue 🔵
* Green 🟢
* Yellow 🟡
* Purple 🟣
* Orange 🟠
* Pink 💗
* Black ⚫
* Brown 🟤
* Gray 🔘
* Salmon 📀

---

# 🎮 Controls

* **TAB** — open/close tablet
* **E / F / LMB** — interact with objects (depending on settings)
* **W A S D** — movement
* **Pause** — open pause menu

> Control settings can be adjusted in `Project Settings` or in the in-game control menu.

---

# 📁 Repository Structure (recommended)

```
/Content
  /Blueprints
  /Maps
  /UI
  /Meshes
/Docs
  /Screenshots
  /Blueprints
README.md
```

---

# 🧩 How to Run the Project (Locally)

1. Install Unreal Engine (version 5.3 or 5.4).
2. Clone this repository:

   ```bash
   git clone <repository>
   ```
3. Open the `.uproject` file via Epic Games Launcher or double-click it.
4. If needed — run `Generate Visual Studio project files` and build the project.

---

# 🤝 Contributing

* Open an issue with bug reports or feature suggestions.
* Pull requests are welcome — describe your changes and tests.
* Before merging, please coordinate Blueprint architecture changes with the author.

---

# 📬 Contact

For inquiries, please open an issue or send an email from my GitHub profile.

---

# ⚖️ License

By default — specify your desired license (MIT, CC-BY, GPL, etc.). I can add a standard LICENSE block if needed.

---

Thanks for reading — I can also:

* Add a detailed Blueprint folder breakdown
* Create an English & Russian dual-language README
* Add GIFs/screenshots for the "Preview" section
* Include badges and CI/versioning instructions


