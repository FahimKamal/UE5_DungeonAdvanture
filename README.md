# ⚔️ Arena Gauntlet 🏹 - (Work In Progress 🚧)

## 🎯 Short Description

Survive the onslaught! **Arena Gauntlet** is a top-down 2D wave-based arena fighter built with Unreal Engine 5.3.3 (Blueprints & PaperZD). Battle increasingly difficult enemies 👾, upgrade your arsenal, and see how long you can last in the arena!

<!-- Optional: Add a cool screenshot or GIF here later! -->
<!-- ![Gameplay GIF](link/to/your/gif.gif) -->

## 📖 About The Game

**Arena Gauntlet** is a 2D top-down arena survival game being developed in Unreal Engine. The core gameplay loop involves the player fighting off waves of enemies within a confined arena (or cave section). After clearing all enemies in a wave, the next, more challenging wave begins 🔥. The difficulty increases over time by introducing stronger enemies and entirely new enemy types.

This project also serves as a learning exercise 💡, particularly focusing on 2D game development workflows within Unreal Engine using **Blueprints** and the **PaperZD** plugin. As an open-source project (MIT License), feel free to explore the code, learn from it, or contribute!

## 📜 Premise

> Ever eager for discovery, a young adventurer strayed from the familiar paths of the village woods, drawn towards a hidden cave entrance veiled by ancient roots. Curiosity overcoming caution, they ventured inside. Deeper they went, until a sudden tremor shook the earth, sealing the entrance behind them in a cascade of rock and soil.
>
> Trapped within the echoing darkness, the adventurer soon realized they were not alone. The depths stirred, and from the shadows emerged waves of strange, hostile creatures – guardians of this hidden place, awakened by the intrusion. With sword and bow readied, the only path to survival – and perhaps, another way out – lies directly through the relentless onslaught.

## ✨ Key Features (Implemented & Planned)

*   🌟 **Top-Down 2D Arena Combat:** Fast-paced action from a top-down perspective.
*   🌊 **Wave-Based Survival:** Face endless or progressively harder waves of enemies.
*   📈 **Increasing Difficulty:** Enemies get tougher, faster, and new types appear as you progress.
*   ⬆️ **Player Progression:** Start with basic gear and acquire new weapons (Sword & Bow planned).
*   🕹️ **8-Directional Player Movement:** Smooth character control (implemented using PaperZD).
*   📘 **Blueprint-Only Project:** Developed entirely using Unreal Engine's Blueprint visual scripting system.
*   🏗️ **Structured Class Hierarchy:** Uses parent/child Blueprints for organized and reusable code (Player and Enemies inherit from a base character).

## 💻 Technology Stack

*   **Engine:** Unreal Engine 5.3.3
*   **Core Logic:** Blueprints
*   **2D Animation/Character Logic:** PaperZD Plugin 📜
*   **Assets:** Freely available public resources 🖼️

##📊 Current Status

*   **Early Development / Prototype** ⏳
*   Basic 8-directional player movement implemented using PaperZD ✅.
*   Parent/Child class structure for Characters (Player/Enemy) established ✅.
*   Core combat loop (attacking, taking damage), enemy AI, wave management system, and weapon mechanics are currently under development or planned 🤔.

## ⌨️ Planned Controls (Subject to Change)

*   **Movement:** WASD / Arrow Keys (standard 8-directional).
*   **Sword Attack:** [Button] - Attacks in the player's current facing/movement direction. 🗡️
*   **Bow Attack:** [Button] - Fires an arrow towards the mouse cursor's position. 🖱️🏹

## ▶️ Getting Started / Running the Project

**Option 1: Play Packaged Build (When Available)** 🎮

*   Once the game reaches a playable state, pre-packaged builds (ZIP files) will be available in the **Releases** section of this GitHub repository.
*   Download the latest release ZIP file.
*   Extract the contents.
*   Run the game executable (e.g., `ArenaGauntlet.exe`). No Unreal Engine installation needed!

**Option 2: From Source (Requires Unreal Engine)** 🔧

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/FahimKamal/UE5_DungeonAdvanture.git
    ```
2.  **Navigate** to the cloned project directory (`UE5_DungeonAdvanture`).
3.  **Install Unreal Engine 5.3.3** (if you haven't already) via the Epic Games Launcher.
4.  **Right-click** the `.uproject` file (`UE5_DungeonAdvanture.uproject`) and select "Generate Visual Studio project files" (even if it's Blueprint-only, this can help ensure everything is set up correctly).
5.  **Open** the `.uproject` file by double-clicking it. This will launch the Unreal Editor and load the project.
6.  **Press Play** in the editor toolbar to run the game.

## 🔮 Future Plans

*   🛠️ Implement core combat mechanics (Sword & Bow).
*   🧠 Develop basic and advanced enemy AI behaviors.
*   🔄 Create the wave spawning and management system.
*   👽 Introduce multiple enemy types with unique characteristics.
*   📊 Add UI elements (Health, Score, Wave Number).
*   ⚖️ Refine gameplay balance and polish features.
*   🖥️ Implement an **introductory screen** displaying the story premise and basic controls/objectives.
*   📦 Provide packaged builds in the Releases section.

## ©️ License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details. This means the project is open source and you are free to use, modify, and distribute it according to the license terms. 📄