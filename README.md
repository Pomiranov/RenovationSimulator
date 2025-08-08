---

# 🏠 Renovation Simulator — Unreal Engine 5 🎮🛠️

[🎥 YouTube Preview ▶️](https://youtu.be/_9fxAEfgmrA)

![Preview Image](https://media.fab.com/image_previews/gallery_images/c745f6f9-ed0e-4ac6-b08f-d7784194cdce/43aad675-916e-4329-961d-0a99ca9c4ed0.jpg)

---

## 📑 Table of Contents | Оглавление

1. [📖 Introduction | Введение](#-introduction--введение)
2. [✨ Key Features | Основные возможности](#-key-features--основные-возможности)
3. [🌅 Day/Night Cycle | Цикл дня и ночи](#-daynight-cycle--цикл-дня-и-ночи)
4. [🎡 Selection Wheel | Колесо выбора](#-selection-wheel--колесо-выбора)
5. [📱 Tablet System | Система планшета](#-tablet-system--система-планшета)
6. [✨ Interaction System | Система взаимодействия](#-interaction-system--система-взаимодействия)
7. [💰 Money System | Система денег](#-money-system--система-денег)
8. [📈 Level System | Система уровней](#-level-system--система-уровней)
9. [🗑️ Garbage and Dirt | Мусор и грязь](#️-garbage-and-dirt--мусор-и-грязь)
10. [🎮 Controls | Управление](#-controls--управление)
11. [📁 Project Structure | Структура проекта](#-project-structure--структура-проекта)
12. [🚀 How to Run | Запуск проекта](#-how-to-run--запуск-проекта)
13. [📬 Contact | Контакты](#-contact--контакты)
14. [⚖️ License | Лицензия](#️-license--лицензия)

---

## 📖 Introduction | Введение

**RU:**
Этот проект с механиками ремонта, кастомизации интерьеров и взаимодействия с объектами. Всё реализовано на **Blueprints** и **C++**.

**EN:**
This project with renovation mechanics, interior customization, and object interaction. Fully implemented in **Blueprints** and **C++**.

---

## ✨ Key Features | Основные возможности

* ⏰ Day/Night Cycle | Цикл дня и ночи
* 📱 Interactive Tablet | Интерактивный планшет
* 💰 Money System | Система денег
* 🗑️ Garbage Collection | Сбор мусора
* 🧽 Dirt Cleaning | Чистка грязи
* 🎨 Painting Walls, Doors, Ceilings | Покраска стен, дверей, потолков
* 🧱 Fence Repair | Ремонт забора
* 🎡 Selection Wheel | Колесо выбора
* 🪙 Sell Items | Продажа предметов
* 📈 Leveling & XP System | Прокачка и опыт
* ✨ Object Outline Interaction | Подсветка объектов
* 🧩 Structure Meshes | Строительные меши
* ⏸️ Pause Menu | Меню паузы
* 🔢 FPS Counter | Счётчик FPS

---

## 🌅 Day/Night Cycle | Цикл дня и ночи

![Day/Night](https://sun9-22.userapi.com/s/v1/if2/fiKmLHu91IVivqvoJ7xSAQazwB-qtFZ7tGdXgHaPXeMSg2F_7V-94H5a5OeCpzaaM0QHpP831NHGo_Gvt3poxwps.jpg?quality=95\&as=32x9,48x13,72x19,108x29,160x43,240x65,360x97,480x129,482x130\&from=bu\&cs=482x0)

**RU:**
Добавьте `BP_TimeDay` в сцену и настройте: Directional Light, Sky Light, Day Length. Часы (`WBP_Clock`) автоматически синхронизированы с циклом.

**EN:**
Add `BP_TimeDay` to your scene and configure: Directional Light, Sky Light, Day Length. The clock (`WBP_Clock`) is automatically synced with the cycle.

---

## 🎡 Selection Wheel | Колесо выбора

![Selection Wheel](https://sun9-81.userapi.com/s/v1/if2/1BfkrScaITNcMb5E40EfruoJY45xfCKDSabZE4cX-8X7wfkJw81rkIPU5Tk5pX4nqC0KuSHYsFX6SXWoHwdxGfM3.jpg?quality=95\&as=32x30,48x45,72x68,108x102,160x151,240x227,360x340,464x438\&from=bu\&cs=464x0)

**RU:**
Данные хранятся в `DT_Tools`. Изменения в базе автоматически обновляют колесо.

**EN:**
Data is stored in `DT_Tools`. Updates in the database automatically refresh the wheel.

---

## 📱 Tablet System | Система планшета

![Tablet](https://sun9-40.userapi.com/s/v1/if2/ZXM192ycf45rHWoUCx0281_fC1vVZpduaHUEGIBWEogoENI3MQs-Z7ypMkcuMAcTwtHUaFdAG3B122_ZHoXq5Lww.jpg?quality=95\&as=32x21,48x32,72x48,108x72,160x107,240x160,360x240,480x320,540x360,640x427,720x480,1080x720,1233x822\&from=bu\&cs=1233x0)

**RU:**
Главный интерфейс для кастомизации интерьера: Paint, Walls, Floors, Ceilings.

**EN:**
Main interface for interior customization: Paint, Walls, Floors, Ceilings.

---

## ✨ Interaction System | Система взаимодействия

![Interaction](https://sun9-66.userapi.com/s/v1/if2/_BzIq3rvKDpeoDlpKHgsPVbUiLMvrFeJJHlth9HGmYxtszC-zf4legMnVmiBH7NM0R85Hu4X0melmC3Qu8EbcCoP.jpg?quality=95\&as=32x14,48x21,72x31,108x47,160x69,240x104,360x156,437x189\&from=bu\&cs=437x0)

**RU:**
Подсветка объектов с возможностью кастомизации толщины и цвета, плюс виджет взаимодействия.

**EN:**
Object outline with customizable thickness and color, plus interaction widget.

---

## 💰 Money System | Система денег

![Money](https://sun9-71.userapi.com/s/v1/if2/A7hAJ8CGu5rHWw47s5TIo_bKdI-3aNVcVnmSQEve2Pa3u8dWqpgIpsupo0y6s5H27w4-q6zVgNsGiG8BaHa1cygk.jpg?quality=95\&as=32x4,48x7,72x10,108x15,160x22,240x34,360x50,480x67,540x76,640x90,714x100\&from=bu\&cs=714x0)

**RU:**
Начальный баланс \$1500. Можно покупать, продавать и изменять баланс через функции.

**EN:**
Starting balance \$1500. Buy, sell, and change balance via functions.

---

## 📈 Level System | Система уровней

![Levels](https://sun9-60.userapi.com/s/v1/if2/OPyRdIrVUL8I3uGvaEZj9HfvjEQ7ne0lCX0a2dqgHNsEFCHMleCqfdbV4Ax8NeXowLnKbz8Sl3pmqi0lCuigjLpm.jpg?quality=95\&as=32x14,48x21,72x32,108x48,160x70,240x106,360x158,480x211,540x238,640x282,668x294\&from=bu\&cs=668x0)

**RU:**
100 уровней по умолчанию. `WBP_Level` отображает прогресс.

**EN:**
100 levels by default. `WBP_Level` displays progress.

---

## 🗑️ Garbage and Dirt | Мусор и грязь

![Garbage](https://sun9-75.userapi.com/s/v1/if2/fcBB1DuwtkY2uV2PWAXpGrnHkO16Kk3_Ac-L01NQt8FuYf5o46us809w16IrNFhRVfZGcKHZkFZVRNc073Ypza29.jpg?quality=95\&as=32x9,48x13,72x20,108x30,160x44,240x66,360x99,480x132,487x134\&from=bu\&cs=487x0)

**RU:**
`BP_Garbage` — объект мусора, даёт XP и добавляет цель в HUD.
`BP_Dirt` — грязь на поверхностях, удаляется губкой.

**EN:**
`BP_Garbage` — trash object, grants XP and adds objective to HUD.
`BP_Dirt` — dirt decal on surfaces, cleaned with sponge.

---

## 🎮 Controls | Управление

![Intro Image](https://sun9-3.userapi.com/s/v1/if2/8_cGNq7AAdtkaOa12orXlv6Lnwu44UBZ2FiCFH-F7wEwPilIQBl8RV2sIXVnrO8mQIVWIMrahMqOKgehfIzAfTPc.jpg?quality=95\&as=32x9,48x14,72x20,108x31,160x45,240x68,360x102,480x136,540x153,640x181,714x202\&from=bu\&cs=714x0)

---

## 📁 Project Structure | Структура проекта

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

## 🚀 How to Run | Запуск проекта

1. Install Unreal Engine 5.3/5.4
2. Clone repo:

```bash
git clone <repository>
```

3. Open `.uproject`
4. (Optional) Generate Visual Studio files and build.

---

## 📬 Contact | Контакты

* **GitHub Issues**
* **Email** — см. профиль GitHub

---

## ⚖️ Displaying development on BluePrints and C++ | Displaying development on BluePrints and C++

## 🌓 Day/Night Cycle Logic

**Initialization (Event BeginPlay):**

* Get the player character and cast to BP_FirstPersonCharacter.
* Store the reference in a variable Player.

**Day/Night Cycle (Event Tick):**

1. Event Tick provides Delta Seconds.
2. Multiply Delta Seconds by Day Length (float) — controls time speed.
3. Pass the result to the Clock function (updates internal time) and rotate Directional Light using Add Actor Local Rotation.
4. Get Actor Rotation and check Pitch:

   * If between **0–100**, it’s considered **night**.
5. Based on the Night Time flag, call NightLighting or DayLighting.

![Day/Night Blueprint Logic](https://sun9-31.userapi.com/s/v1/if2/r3k_4QrB-AH6gpEroxdzXV6VjmW6CptQn6WcR1aokgrS5fTHXOrW8wtWpRSC_sFpWPMSGBXyPlV2808J8vrSwuvC.jpg?quality=95\&as=32x16,48x24,72x36,108x54,160x80,240x119,360x179,480x239,540x269,640x318,720x358,1080x537,1280x637,1440x716,2048x1019\&from=bu\&cs=2048x0)

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

## ⚙️ Logic

Each button in the tablet interface calls the `Change Content` function in the `WBP Tablet` widget.

### Main flow:
1. The user clicks a button in the menu.
2. The **On Clicked** event is triggered.
3. The **Change Content** function is called with the `Content` parameter corresponding to the selected section.
4. The tablet hides the current screen and displays the selected content.
5. On the content screen, the user chooses a material/color, which is then applied in the scene.

![Tablet](https://sun9-25.userapi.com/s/v1/if2/bqlwnqx2nv_VitvvjOb4GbNJVojP1n5rd1-MR_Aw1dcu1H9Edxc4zDVCXZ7Nn8Btrkh1gkGnsvT7eFusrmqisM1h.jpg?quality=95&as=32x18,48x27,72x40,108x60,160x90,240x134,360x202,480x269,540x302,640x358,720x403,1080x605,1280x717,1440x806,1541x863&from=bu&cs=1541x0)

---

## 🗂 Button and content structure

| Button               | Loaded Content       | Purpose                             |
|----------------------|----------------------|--------------------------------------|
| `Button_Back`        | Content Menus        | Return to the main menu              |
| `Button_Paint`       | Content Paint        | Wall color palette                   |
| `Button_Walls`       | Content Walls        | Decorative panel selection           |
| `Button_Floors`      | Content Floors       | Floor texture selection              |
| `Button_Ceilings`    | Content Ceiling      | Ceiling paint selection              |

---

### ⚙️ Selection Wheel Logic
1. **Loading the tools database**  
   On startup, the `DT_Tools` Data Table is read, the number of items is counted, and the corresponding number of wheel segments is set.

2. **Creating icons**  
   For each tool, an icon widget is created and added to the selection wheel.

3. **Dynamic material**  
   - Controls the visual display of the segments.  
   - Allows adjusting the **sector size** depending on the number of tools.  
   - Highlights the active sector.

4. **Tool selection**  
   - A red border around a sector indicates the current selection.  
   - The tool is selected when the wheel key is released.  
   - By default, the selected tool is **Hands (`Tool_01`)**.

### 🖼 Blueprint logic example
The Blueprint contains the following blocks:
- **Tools database** — loading and processing `DT_Tools`.
- **Icons** — creating and displaying tool icons in the wheel.
- **Material Instance** — configuring the dynamic material.
- **Sector Size** — calculating the size of each segment.
- **Sector Selection** — determining the currently selected sector.
- **Update Sector** — updating the wheel state in `Tick`.

![WheelLogic](


