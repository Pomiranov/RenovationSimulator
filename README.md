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
14. [⚙️ Displaying development on BluePrints and C | Показ разработки на Блюпринтах и C
](#️-displaying-development-on-blueprints-and-c--показ-разработки-на-блюпринтах-и-c)

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

## ⚙️ Displaying development on BluePrints and C | Показ разработки на Блюпринтах и C

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

### 🎡 Selection Wheel Logic
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

![WheelLogic](https://sun9-83.userapi.com/s/v1/if2/DeR2IX7Sbgol9JkwhvY5W9ei5yCcnxIiPMWd6ePV0a3uNKbiE-pN52aNez0tF7EtXpLxLhcSWcarOoRVPa87Spfa.jpg?quality=95&as=32x8,48x13,72x19,108x29,160x42,240x64,360x95,480x127,540x143,640x170,720x191,1080x286,1280x339,1440x382,2048x543&from=bu&cs=2048x0)

---
# 🎮 Main Menu System

![MainMenu](https://sun9-36.userapi.com/s/v1/if2/EmEtST6y48bORIIbnLASbA8DIo5hnTESX6F-iurI_CSSKm6pApthlxoqs3MH_U4x3ykFWltMXZ4sFjt9UzTvMKmW.jpg?quality=95&as=32x18,48x27,72x40,108x61,160x90,240x135,360x202,480x269,540x303,640x359,720x404,1080x606,1124x631&from=bu&cs=1124x0)
### 📋 Description
The main menu in the game is opened by pressing the **P** key.  
It is the central tablet element managed in the main widget and is responsible for displaying the content in the tablet based on the selected section.  
The main menu is composed of a grid of buttons. Each button calls the `Change Content` function via the **On Clicked** event.

---

### 🎯 Button functionality
- **Resume** — resumes the game.
- **Options** — in development (no functionality yet, but will be added in the future).
- **Main menu** — restarts the game.
- **Leave game** — exits the game.

---

### ⚙️ Logic
1. Pressing **P** opens the main menu.
2. The **Resume** button calls the `Pause Hide` function, returning the player to the game.
3. The **Options** button currently has no bound logic.
4. The **Main menu** button calls `Pause Hide` and then executes `Open Level`, restarting the current scene.
5. The **Leave game** button gets the player controller and executes the `Quit Game` command.

---
![Main](https://sun9-21.userapi.com/s/v1/ig2/iq4X4joT6EG-ipkDQxfYhD40uRPhGLhPAtzrXqUCCqqapljSTWXGCF1JZ88p6R5YRTHkkK5W1nmdIqm6UWw5UKty.jpg?quality=95&as=32x36,48x53,72x80,108x120,160x178,240x267,360x401,480x535,540x601,640x713,720x802,817x910&from=bu&cs=817x0)

### 🖥 Blueprint Workflow
#### **Initialization**
- When the widget is created (`Event Construct`), it retrieves the player using `Get Player Character`.
- The retrieved object is cast to `BP_FirstPersonCharacter` and stored in the `Player` variable for later use.

#### **Resume button**
- The **On Clicked (Button_Resume)** event calls the `Pause Hide` function on the stored player object, hiding the menu and resuming the game.

#### **Main menu**
- The **On Clicked (Button_Main)** event calls `Pause Hide`, then executes `Open Level (by Name)` with the specified level name (default: `Demo`), restarting the scene.

#### **Leave button**
- The **On Clicked (Button_Leave)** event gets the player controller (`Get Player Controller`) and executes the `Quit Game` command, exiting the game.

---

# Unreal Engine 5 Day/Night Cycle & Clock System 🌞🌙

## 📜 Overview / Обзор

This system is responsible for simulating a day and night cycle in the game world. The day/night cycle affects various aspects of the game, such as lighting, and is controlled by an internal clock. The cycle is designed to speed up or slow down based on the developer's preferences, allowing more flexibility in gameplay or simulation scenarios.

Эта система отвечает за имитацию цикла дня и ночи в игровом мире. Цикл дня и ночи влияет на различные аспекты игры, такие как освещение, и управляется внутренними часами. Цикл можно ускорить или замедлить в зависимости от предпочтений разработчика, что позволяет больше гибкости в геймплейе или симуляциях.

---

## ⚙️ Blueprint Breakdown / Разбор блюпринта

### **Initialization (Event Begin Play) / Инициализация (Событие Begin Play)**

- **Get Player Character**: The blueprint begins by retrieving the player character when the game starts (Event Begin Play).  
  **Получить персонажа игрока**: Блюпринт начинается с получения персонажа игрока, когда игра запускается (Событие Begin Play).

- **Cast to BP_FirstPersonCharacter**: The player character is cast to a specific blueprint class (`BP_FirstPersonCharacter`) to ensure proper referencing.  
  **Каст к BP_FirstPersonCharacter**: Персонаж игрока кастуется в конкретный класс блюпринта (`BP_FirstPersonCharacter`) для правильного ссылки.

- **Set Player**: After casting, the player reference is set for further use within the system.  
  **Установить Player**: После кастования создается ссылка на игрока, которая используется в дальнейшем.

![Blueprints](https://sun9-47.userapi.com/s/v1/if2/QKbNLbiv1BXm27rcYQEc72D2yy_XO-nVUndKg4XSFEf9Z7-i4bvEELkpMh-8KEFNa_HvvBO1vOrTFocUeOZGZxC2.jpg?quality=95&as=32x12,48x18,72x27,108x40,160x59,240x89,360x133,480x178,540x200,640x237,720x266,1080x399,1280x473,1440x533,2063x763&from=bu&cs=2063x0)

---

### **🎉Day/Night Cycle (Event Tick) / Цикл дня и ночи (Событие Tick)**

The core of the system updates every frame (Event Tick) to simulate the passage of time. Here's the breakdown:

Основная часть системы обновляется каждый кадр (Событие Tick), чтобы симулировать прохождение времени. Вот разбор:

1. **Clock Update / Обновление часов**:
   - The clock system continuously tracks the passage of time (controlled by the variable `Day Length`).  
     **Часы**: Система часов непрерывно отслеживает прохождение времени (управляется переменной `Day Length`).

   - The clock is directly connected to the day/night cycle, so speeding up the cycle will cause the clock to run faster as well.  
     **Цикл дня и ночи**: Часы напрямую связаны с циклом дня и ночи, поэтому ускоряя цикл, вы ускоряете и работу часов.

2. **Actor Rotation (Directional Light) / Поворот актора (Направленный свет)**:
   - The system continuously updates the rotation of the directional light (which simulates the sun or moon) based on the time of day.  
     **Поворот актора (Направленный свет)**: Система обновляет поворот направленного света (симулирующий солнце или луну) в зависимости от времени суток.

   - The `Add Actor Local Rotation` node adjusts the light's pitch in relation to the game world, making the lighting change as the day progresses.  
     **Изменение угла поворота**: Узел `Add Actor Local Rotation` регулирует угол наклона света относительно игрового мира, заставляя освещение изменяться с течением дня.

3. **Determine If It's Day or Night / Определение, день ли сейчас или ночь**:
   - The system checks if the time of day is within the defined range for daytime or nighttime using an `In Range (Float)` check.  
     **Определение дня или ночи**: Система проверяет, попадает ли время суток в определенный диапазон дня или ночи с помощью проверки `In Range (Float)`.

   - If the time falls within the designated night period, the `Night Lighting` function is activated.  
     **Если ночь**: Если время попадает в диапазон ночного времени, активируется функция `Night Lighting`.

   - If it's daytime, the `Day Lighting` function is used.  
     **Если день**: Если день, используется функция `Day Lighting`.

4. **Lighting / Освещение**:
   - Depending on the time of day, the lighting for both day and night are adjusted to simulate realistic lighting effects.  
     **Освещение**: В зависимости от времени суток освещение для дня и ночи изменяется для симуляции реалистичных световых эффектов.

   - The `NightLighting` and `DayLighting` functions adjust the environmental light to reflect either a night-time or day-time setting.  
     **Функции освещения**: Функции `NightLighting` и `DayLighting` регулируют окружение света для отображения ночного или дневного времени.
![Blueprints](https://sun9-23.userapi.com/s/v1/if2/TfNrG1RKyZjLGANo0vkcJnjkuEZaj3tq_Nid4qMHh0XdRKjNMXou6Cgs-a75Xs4mBj4kls_SqwCYRohHaG8sKpfn.jpg?quality=95&as=32x18,48x27,72x40,108x60,160x89,240x133,360x200,480x266,540x299,640x355,720x399,1080x599,1280x710,1440x798,1703x944&from=bu&cs=1703x0)
![Blueprints](https://sun9-63.userapi.com/s/v1/if2/GHkwQ28x7gHX9YCrJ2ktMgaQAGu2I9GLMZpJFAeiplyHLwBLxkzv2NlDQicw9Jf2KOYlvvdKzNQvJu5oau0nl01L.jpg?quality=95&as=32x18,48x26,72x40,108x60,160x88,240x132,360x199,480x265,540x298,640x353,720x397,1080x596,1280x706,1440x794,1704x940&from=bu&cs=1280x0)
---

## ⏰ Clock Widget / Виджет часов

The clock system also has a user interface component. To display the clock in the game's HUD:

Система часов также имеет компонент пользовательского интерфейса. Чтобы отображать часы в HUD игры:

1. **Adding the Clock to HUD / Добавление часов в HUD**:
   - The clock can be added to the user interface by placing the child widget (`WBP_Clock`) into your main widget.  
     **Добавление часов в HUD**: Вы можете добавить часы в интерфейс пользователя, поместив дочерний виджет (`WBP_Clock`) в основной виджет.

   - You can find the clock widget in the `/Blueprints/Widgets/Childs` folder in your project directory.  
     **Папка с виджетом**: Виджет часов находится в папке `/Blueprints/Widgets/Childs` вашего проекта.

2. **Day Count / Подсчет дней**:
   - The number of days in the game is automatically tracked and updated at the end of each day at 0:00.  
     **Подсчет дней**: Количество дней в игре автоматически отслеживается и обновляется в конце каждого дня в 00:00.
     
![Blueprints](https://sun9-11.userapi.com/s/v1/if2/52U_Ous104yhOhgah9zQl5uek3sIOU2DXOIJjFYQ4nDGTMRSy-091gv8OyTmfhPOhId8qr4UFYeYOy_9qI7F4h86.jpg?quality=95&as=32x11,48x16,72x24,108x36,130x43&from=bu&cs=130x0)

---

## 🎯 Conclusion / Заключение

This system provides an efficient and flexible way to manage time within your game, enabling seamless transitions between day and night. The clock is not only tied to the lighting but can also be extended for other features such as event triggers based on time.

Эта система предоставляет эффективный и гибкий способ управления временем в вашей игре, позволяя легко переключаться между днем и ночью. Часы не только связаны с освещением, но могут быть расширены для других функций, таких как активация событий в зависимости от времени.

---

Feel free to adjust the parameters such as `Day Length` to change the speed of the cycle. You can also expand the clock widget for more advanced UI displays if needed.

Не стесняйтесь настроить параметры, такие как `Day Length`, чтобы изменить скорость цикла. Вы также можете расширить виджет часов для более сложных элементов UI, если это необходимо.

---

# Character Blueprint Overview / Обзор Блюпринта Персонажа

## 📝 Introduction / Введение

This blueprint is responsible for managing a variety of key gameplay systems, such as input mapping, character movement, interaction, tool usage, camera control, and more. Here's a breakdown of the key components in this blueprint:

Этот блюпринт управляет множеством ключевых систем геймплея, таких как маппинг ввода, движение персонажа, взаимодействие, использование инструментов, управление камерой и многое другое. Вот разбор основных компонентов этого блюпринта.

![Blueprints](https://sun9-16.userapi.com/s/v1/if2/EpnWnETP86pOeP_zcUtUv3yAxegBYK7AiJHSAwuxJvAFJZNIWmcofQNrydpo-aHlYlPfuPM_kaswulHh5y5upOp0.jpg?quality=95&as=32x13,48x20,72x30,108x45,160x67,240x100,360x151,480x201,540x226,640x268,720x301,1080x452,1280x535,1440x602,1855x776&from=bu&cs=1280x0)

---

## ⚙️ Initialization / Инициализация

- **Event Begin Play**: When the game begins, the blueprint initializes by retrieving the player character and setting up necessary variables such as the player reference.  
  **Событие Begin Play**: Когда игра начинается, блюпринт инициализируется, получая персонажа игрока и устанавливая необходимые переменные, такие как ссылка на игрока.

- **Add Input Mapping**: The input mappings are configured, and it listens for controller changes to ensure proper handling of player input during the game session.  
  **Добавление маппинга ввода**: Маппинг ввода настраивается, и блюпринт отслеживает изменения контроллера для правильной обработки ввода игрока во время игры.

---

## 🎮 Camera Control / Управление Камерой

- **Camera Input**: This section handles camera movement, allowing the player to control the camera’s orientation. Input is mapped to certain actions (like rotating the camera left/right and up/down).  
  **Управление камерой**: Этот раздел обрабатывает движение камеры, позволяя игроку контролировать её ориентацию. Ввод связан с определёнными действиями (например, вращение камеры влево/вправ и вверх/вниз).

---

## 🚶‍♂️ Movement Input / Ввод Движения

- **Left/Right Movement**: The blueprint handles the player's left and right movement, allowing horizontal motion.  
  **Движение влево/вправ**: Блюпринт обрабатывает движение игрока влево и вправо, позволяя горизонтальное движение.

- **Up/Down Movement**: Similarly, vertical movement (e.g., jumping or crouching) is handled.  
  **Движение вверх/вниз**: Аналогично, вертикальное движение (например, прыжки или приседания) также обрабатывается.

- **Forward/Backward Movement**: The blueprint also includes functionality for moving the player forward and backward, typically tied to the W and S keys (or corresponding controller buttons).  
  **Движение вперёд/назад**: Блюпринт также включает функциональность для движения персонажа вперёд и назад, обычно привязанных к клавишам W и S (или соответствующим кнопкам контроллера).

These movement inputs are managed using the `Enhanced Input` system for both axis-based controls and specific actions.  
Эти вводы движения управляются с использованием системы `Enhanced Input` для контроля по осям и конкретных действий.

---

## 🦸‍♂️ Jumping / Прыжки

- **Jump Input**: The blueprint listens for the jump action (usually the spacebar or controller button) and triggers the jump behavior. Jumping functionality can be configured in the `CharacterMovementComponent`.  
  **Ввод прыжка**: Блюпринт отслеживает действие прыжка (обычно клавиша пробела или кнопка контроллера) и вызывает поведение прыжка. Функциональность прыжка можно настроить в компоненте `CharacterMovementComponent`.

---

## 🔄 Interaction System / Система Взаимодействия

- **Interaction**: The blueprint handles the system for interacting with objects within the game world. When the player looks at an interactable object, the game can trigger the appropriate action and show the relevant interaction UI.  
  **Взаимодействие**: Блюпринт управляет системой взаимодействия с объектами в игровом мире. Когда игрок смотрит на взаимодействуемый объект, игра может вызвать соответствующее действие и отобразить нужный интерфейс взаимодействия.

---

## 🛠️ Tool Actions / Действия Инструментов

- **Tool Selection Wheel**: This section provides a selection wheel for tools, where the player can select various tools for different tasks. The wheel uses dynamic materials, and players can easily customize tool selection. When a player releases the wheel button, the currently selected tool is chosen (default being "hands").  
  **Колесо выбора инструмента**: Этот раздел предоставляет колесо выбора инструментов, где игрок может выбрать различные инструменты для разных задач. Колесо использует динамические материалы, и игроки могут легко настроить выбор инструментов. Когда игрок отпускает кнопку колеса, выбранный инструмент активируется (по умолчанию — "руки").

- **Tool Animation**: When a tool is selected and used, the tool's animation is played (such as a brush animation for cleaning or a hammer animation for repairs).  
  **Анимация инструмента**: Когда инструмент выбран и используется, воспроизводится его анимация (например, анимация кисти для уборки или анимация молотка для ремонта).

---

## 📱 Tablet Interface / Интерфейс Плана

- **Show/Hide Tablet**: The tablet UI can be shown or hidden based on player input. The tablet is central to various in-game tasks, and it includes the main menu and other interactive widgets for controlling gameplay.  
  **Показать/Скрыть планшет**: Интерфейс планшета может быть показан или скрыт в зависимости от ввода игрока. Планшет является центральным элементом для различных игровых задач и включает главное меню и другие интерактивные виджеты для управления игровым процессом.

- **Contents Management**: Widgets on the tablet are dynamically shown and switched based on player interaction. Players can easily modify content within the tablet, allowing for a customizable user experience.  
  **Управление содержимым**: Виджеты на планшете динамически отображаются и переключаются в зависимости от взаимодействия с игроком. Игроки могут легко изменять содержимое планшета, предоставляя кастомизируемый опыт пользователя.

---

## 🌅 Day/Night Cycle and Level Management / Цикл Дня/Ночи и Управление Уровнями

- **Day/Night Cycle Instance**: The blueprint includes logic for managing day and night transitions, ensuring proper environmental changes based on the time of day.  
  **Инстанс Цикла Дня/Ночи**: Блюпринт включает логику для управления переходами между днем и ночью, обеспечивая правильные изменения окружающей среды в зависимости от времени суток.

- **Level Interaction**: This system ensures that the player's interaction with objects and the environment is tracked properly, including triggering levels or objectives based on player actions.  
  **Взаимодействие с Уровнями**: Эта система отслеживает взаимодействие игрока с объектами и окружающей средой, включая активацию уровней или целей в зависимости от действий игрока.

---

## ☕ Pause Menu and UI / Меню Паузы и Интерфейс

- **Pause Menu**: The blueprint includes functionality for displaying the pause menu when the player presses the pause button (`P`). This allows the player to interact

---

## ❗ Автор позже закинет сюда разработку на C++/The author will add the C++ development here later.


