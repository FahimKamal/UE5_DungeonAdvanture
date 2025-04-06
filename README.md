# ⚔️ Arena Gauntlet 🏹 - v1.0

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.3.1-blueviolet)](https://www.unrealengine.com/)
[![Made with Blueprints](https://img.shields.io/badge/Made%20with-Blueprints-blue)](https://docs.unrealengine.com/en-US/Engine/Blueprints/index.html)
[![PaperZD](https://img.shields.io/badge/Uses-PaperZD-orange)](https://www.fab.com/listings/6664e3b5-e376-47aa-a0dd-f7bbbd5b93c0) <!-- Adjust if PaperZD has a specific badge/link -->


---
https://github.com/user-attachments/assets/3dbda578-d050-403c-8b58-6c531a1f3881

<!-- 
======================================================================
=== VISUAL SHOWCASE - BEST PLACE FOR A GIF/KEY SCREENSHOT! ===
======================================================================
Highly recommend adding an animated GIF (15-30s loop) or a compelling screenshot here. 
This is the first thing people see!
- Create a short video clip (around 1 minute as you planned, then convert a key segment to GIF).
- Tools like ScreenToGif (Windows) or online converters can help. Keep GIF size reasonable (<10-15MB ideally).
- Consider creating a 'Docs' or 'Media' folder in your repository to store these images/gifs.

Example (replace with your actual file path):
-->
<p align="center">
  <!-- <img src="Docs/arena_gauntlet_gameplay.gif" alt="Arena Gauntlet Gameplay GIF" width="80%"/> -->
  <!-- Or Link to a gameplay video on YouTube/Vimeo if you prefer: -->
  <!-- **[Watch Gameplay Video (1 Min)](https://your-video-link-here)** -->
</p>

---

## 🎯 Overview

**Survive the onslaught!** **Arena Gauntlet** is a fast-paced, top-down 2D wave-based arena fighter built entirely with **Unreal Engine 5.3.1** using **Blueprints** and the **PaperZD** plugin. Battle waves of increasingly difficult enemies 👾, find power-ups, master sword and bow combat, and push your survival skills to the limit in a mysterious, monster-infested cave!

This project serves as both a playable game prototype and a demonstration of skills acquired in Unreal Engine 2D development, Blueprint scripting, and core game systems implementation.

---

## 📜 Premise

> Ever eager for discovery, a young adventurer strayed from the familiar paths of the village woods, drawn towards a hidden cave entrance veiled by ancient roots. Curiosity overcoming caution, they ventured inside. Deeper they went, until a sudden tremor shook the earth, sealing the entrance behind them in a cascade of rock and soil.
>
> Trapped within the echoing darkness, the adventurer soon realized they were not alone. The depths stirred, and from the shadows emerged waves of strange, hostile creatures – guardians of this hidden place, awakened by the intrusion. With sword and bow readied, the only path to survival – and perhaps, another way out – lies directly through the relentless onslaught.

---

## ✨ Key Features

*   🌟 **Top-Down 2D Arena Combat:** Intense, reactive combat in a confined arena.
*   🌊 **Wave-Based Survival:** Face progressively harder waves of enemies with dynamic spawning.
*   🕹️ **Responsive 8-Directional Movement:** Smooth character control powered by PaperZD.
*   ⚔️ **Melee & Ranged Combat:** Master the **Sword** (2 Damage, requires proximity) and unlock the **Bow** (1 Damage, fires in facing direction).
*   👾 **Varied Enemies:** Battle distinct foes like the durable **Skeleton** (3 HP) and the charging **Boar** (2 HP).
*   ❤️ **Health System with Pickups:** Manage your 3 starting health points and find **Health Pickups** to restore 1 HP.
*   🏹 **Unlockable Ability:** Find the **Bow Pickup** to enable ranged attacks permanently.
*   🛡️ **Combat Feedback:** Experience **knockback** (player & enemies), **damage flashes** (red tint), temporary **invincibility frames** (player, 2 secs with flickering), and satisfying **enemy death VFX** (skull explosion).
*   🔊 **Immersive Audio:** Features **background music**, player **footsteps**, distinct sounds for **sword/bow attacks**, enemy attacks, **hits** (player/enemy), **pickups** (unique for health/bow), and enemy deaths.
*   🖥️ **Essential UI:** Includes a **Main Menu** (Play/Quit), dynamic **Health Bar** (heart icons), and a clear **Game Over/Win Screen**.
*   🧱 **Contained Arena:** A well-defined level with wall boundaries for focused gameplay.
*   💡 **Data-Driven Design:** Wave compositions are managed via a **Data Structure**, read by a central **Spawning Manager**.
*   📘 **100% Blueprint Project:** Developed entirely using Unreal Engine's powerful Blueprint visual scripting system – no C++ required.

---

<!-- 
======================================================================
=== ADDITIONAL SCREENSHOTS (Optional Section) ===
======================================================================
If you have multiple static screenshots you want to showcase (e.g., different UI screens, 
specific combat moments, enemy types), you can add a dedicated section like this.


-->
## 📸 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/189a0382-7552-4cc3-a8db-3a258d71a05a" alt="Screenshot 1 Description" width="45%"/> 
  <img src="https://github.com/user-attachments/assets/d643ef27-75c2-4bdc-b023-da49bdfe5769" alt="Screenshot 2 Description" width="45%"/>
  <img src="https://github.com/user-attachments/assets/d73de29a-29aa-4f61-ad21-deb25abd1992" alt="Screenshot 3 Description" width="45%"/> 
  <img src="https://github.com/user-attachments/assets/2a5d410a-2d46-428e-a815-2629c22ff00f" alt="Screenshot 4 Description" width="45%"/>
</p>
<!-- [Screenshot 2025-04-07 003901](https://github.com/user-attachments/assets/189a0382-7552-4cc3-a8db-3a258d71a05a)
[Screenshot 2025-04-07 004811](https://github.com/user-attachments/assets/d643ef27-75c2-4bdc-b023-da49bdfe5769)
[Screenshot 2025-04-07 004411](https://github.com/user-attachments/assets/d73de29a-29aa-4f61-ad21-deb25abd1992)

[Screenshot 2025-04-07 004321](https://github.com/user-attachments/assets/2a5d410a-2d46-428e-a815-2629c22ff00f) -->


---

## 💻 Technology Stack

*   **Engine:** Unreal Engine 5.3.1
*   **Core Logic:** Blueprints
*   **2D Animation/Character Logic:** PaperZD Plugin 📜
*   **Assets:** Freely available public resources & custom logic 🖼️

---

## 📊 Project Status (v1.0)

*   ✅ **Complete Core Loop:** Playable from Main Menu to Game Over/Win condition.
*   ✅ **Feature Complete (v1.0 Scope):** All planned core mechanics for this initial version are implemented.
*   ✅ **Stable Build Available:** See the Releases section!

---

## ⌨️ Controls

*   **Movement:** WASD / Arrow Keys (8 Directions)
*   **Sword Attack:** [Button - e.g., Left Mouse Button] - Melee attack in facing direction (requires proximity).
*   **Bow Attack:** [Button - e.g., Right Mouse Button] - Fires an arrow in facing direction (Requires Bow Pickup).
*   **Menu Interaction:** Mouse Click

---

## ▶️ Getting Started / Running the Project

**Option 1: Play Packaged Build (Recommended for Players)** 🎮

1.  Go to the **[Releases](https://github.com/FahimKamal/UE5_DungeonAdvanture/releases)** section of this repository.
2.  Download the latest `ArenaGauntlet_vX.X.zip` file.
3.  Extract the contents of the ZIP file.
4.  Run the game executable (e.g., `ArenaGauntlet.exe`). No Unreal Engine installation needed!

**Option 2: From Source (For Developers - Requires Unreal Engine 5.3.1)** 🔧

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/FahimKamal/UE5_DungeonAdvanture.git
    ```
2.  **Navigate** to the cloned project directory (`UE5_DungeonAdvanture`).
3.  **Ensure Unreal Engine 5.3.1** is installed via the Epic Games Launcher.
4.  **Right-click** the `.uproject` file (`UE5_DungeonAdvanture.uproject`) and select "Generate Visual Studio project files".
5.  **Open** the `.uproject` file by double-clicking it.
6.  **Press Play** in the editor toolbar to run the game.

---

## 🌱 Learning & Development Insights

This project was a valuable deep dive into creating a 2D game within Unreal Engine, focusing entirely on **Blueprints**. Key learning areas included:

*   **2D Workflow:** Utilizing PaperZD for efficient sprite animation and state management.
*   **Combat Systems:** Implementing melee/ranged attacks, damage models, health, knockback, and invincibility frames.
*   **AI Basics:** Creating simple enemy detection, pathfinding (move-to), and attack triggers.
*   **Game Loop Management:** Designing wave progression, enemy tracking, and win/loss conditions.
*   **Modular Design:** Using Blueprint Components (`BPC_Health`) for reusable systems.
*   **Data Management:** Employing Data Structures for scalable wave design via a Spawning Manager.
*   **UI Implementation:** Creating menus and dynamic HUD elements using UMG.
*   **Audio Integration:** Implementing various sound effects and background music.

---

## 🔮 Future Plans / Potential Enhancements

While v1.0 is complete, potential future directions could include:

*   ✨ **More Content:** Adding new enemy types, more complex wave patterns, additional pickup types (e.g., temporary power-ups).
*   🎨 **Visual Variety:** Introducing different player character skins/options.
*   🗺️ **Level Expansion:** Creating multiple arenas/levels with distinct environments (e.g., brighter vs. darker themes).
*   ⏸️ **Pause Menu:** Implementing in-game pause functionality.
*   💯 **Scoring System:** Adding a score tracker for player performance.
*   ⚙️ **Further Polish:** Refining animations, balancing difficulty, and enhancing visual effects.

---

## ©️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to use, modify, and distribute it according to the license terms. 📄
