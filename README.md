# KARS — 2D Story-Driven Action Game

## 📌 Overview

KARS is a 2D story-driven action game developed using Godot Engine. The project combines pixel-art combat, cinematic boss encounters, narrative progression, save systems, and layered parallax environments to create an immersive gameplay experience.

The game focuses heavily on atmosphere, gameplay feel, and cinematic storytelling where the player must survive increasingly dangerous encounters while uncovering the motives of the main antagonist, **Erythro**.

---

## 🎯 Objective

To build a polished 2D action experience capable of:

* Story-driven gameplay progression
* Responsive combat mechanics
* Cinematic boss encounters
* Save/load functionality
* Layered parallax environments
* Smooth UI and menu systems

---

## 🧠 Core Features

* ⚔️ Melee Combat System
* 👹 Enemy AI & Boss Encounters
* 💾 Manual Save & Autosave System
* 🎬 Story & Lore Progression
* 🌌 Multi-Layer Parallax Backgrounds
* 📊 Player Statistics Tracking
* ❤️ Player & Boss Health Systems
* 🕹️ Keyboard Navigation Support
* ☠️ Game Over & Recovery Flow
* 🚪 Portal-Based Level Transitions

---

## 🏗️ Game Systems

### Combat System

* Sword, Axe, and Spear combat support
* Enemy attack and damage handling
* Difficulty-based combat balancing
* Boss-only damage mechanics
* Knockback and hit detection

### Save System

* Multiple manual save slots
* Autosave functionality
* Latest save detection
* Save deletion support
* Pause menu save/load integration

### UI System

* Main Menu
* Pause Menu
* Game Over Menu
* Save & Load Menus
* Difficulty Selection Menu
* HUD & Boss Health Bars
* Statistics Screen

---

## 🎮 Gameplay Flow

1. **Prologue Begins**

   * Player learns basic mechanics.
   * Initial enemies and systems are introduced.

2. **Boss Encounter**

   * The player faces the Prologue Boss.
   * Combat introduces question-based mechanics.

3. **Portal Transition**

   * The player accesses Level 1 using an interactable portal.

4. **Erythro Encounter**

   * The main antagonist appears.
   * The fight is scripted to end in defeat.
   * Erythro escapes after critically injuring the hero.

5. **Story Progression**

   * Lore scenes bridge major levels.
   * The player begins hunting Erythro.

---

## 👹 Main Antagonist — Erythro

Erythro serves as the primary antagonist of the game.

The character is designed around:

* High aggression
* Cinematic presentation
* Psychological pressure during encounters
* Story-driven scripted events

The first encounter intentionally makes the player believe victory is possible before the boss overwhelms the protagonist in a scripted sequence.

---

## 🌌 Environment System

The game uses a layered parallax environment system.

### Background Layers

* Towers
* Multiple cloud layers
* Foreground bridge layer

Each layer moves at different speeds relative to the camera to create depth and atmosphere.

---

## 🏗️ Project Structure

```text
res://
├── scenes/
│   ├── MainMenu.tscn
│   ├── PauseMenu.tscn
│   ├── GameOverMenu.tscn
│   ├── LoadGameMenu.tscn
│   ├── DifficultyMenu.tscn
│   ├── Prologue.tscn
│   ├── Level1.tscn
│   ├── PrologueBoss.tscn
│   ├── Erythro.tscn
│   ├── Portal.tscn
│   ├── HUD.tscn
│   └── BossHealthBar.tscn
│
├── scripts/
│   ├── player.gd
│   ├── GameManager.gd
│   ├── SaveManager.gd
│   └── UI scripts
│
├── backgrounds/
├── enemies/
├── player_assets/
└── effects/
```

---

## 💻 Engine & Technologies

* Godot Engine 4.x
* GDScript
* Pixel Art Animation Pipeline
* Parallax Background System

---

## ⚙️ Save System Workflow

### Manual Saves

* Save progress into dedicated slots.
* Stores:

  * Player health
  * Scene position
  * Enemy states
  * Statistics
  * Difficulty

### Autosave

* Triggered during major progression moments.
* Automatically restores latest progress.

### Latest Save Logic

The system dynamically checks:

* Autosaves
* Manual saves

Whichever save was created most recently becomes the active latest save.

---

## 🕹️ Controls

```text
Arrow Keys / WASD -> Movement
Attack Keys       -> Combat
Up                -> Interact / Portal
Enter             -> Confirm
B                 -> Back
Y                 -> Delete Save
ESC               -> Pause
```

---

## 🚀 Running the Project

### 1. Clone Repository

```bash
git clone https://github.com/your-username/KARS.git
```

```bash
cd KARS
```

---

### 2. Open in Godot

* Open Godot Engine 4.x
* Import the project
* Run the main scene

---

## 📊 Current Features Implemented

* ✅ Combat System
* ✅ Enemy System
* ✅ Boss Encounters
* ✅ Save & Load System
* ✅ Autosave System
* ✅ Statistics Tracking
* ✅ Portal Transitions
* ✅ Pause Menu
* ✅ Game Over System
* ✅ Difficulty Selection
* ✅ Layered Backgrounds

---

## 🔮 Planned Features

* Additional bosses
* Expanded lore scenes
* Advanced AI behavior
* More environments
* Audio integration
* Combo mechanics
* Weapon upgrades
* Improved visual effects

---

## 👥 Developed By

Hari
Engineering Student
Lovely Professional University

---

## 📜 License

This project is currently under active development.

For academic, learning, and portfolio purposes.

---

## 📌 Development Status

### Active Development

Core gameplay systems, save architecture, combat mechanics, UI systems, and cinematic progression systems are already functional.

The project continues to expand with additional content, gameplay systems, and polish.
