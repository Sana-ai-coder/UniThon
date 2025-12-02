<img width="1200" alt="main_menu_background" src="https://github.com/user-attachments/assets/0b29a276-c9c4-4f2f-a527-0312026925fc" />

# UniThon — College Adventure Arcade Game

UniThon is a fast-paced 2D arcade game built using the Godot Engine (GDScript).
You play as a student trying to reach college by navigating through a busy city full of vehicles, crowds, and unexpected obstacles — all while racing against time!

---

## Table of Contents

- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [How to Run the Project](#how-to-run-the-project)
- [Project Structure](#project-structure)
- [Developer Notes](#developer-notes)
- [Contributing](#contributing)
- [Developed By](#developed-by)

---

## 🌟 Key Features

### 🚶 Player Abilities

Smooth Movement: Move in all four directions (WASD / Arrow Keys), including diagonal movement.

Realistic Physics: Responsive controls with proper collision handling.

Immersive Interactions: Experience voice lines during close calls and dynamic reactions to near-miss moments.

### 🚗 Environment & Obstacles

Traffic Challenge: Dodge cars and vehicles with varying speeds.

Crowded Footpaths: Navigate through pedestrians and congested pathways.

Environmental Hazards: Avoid manholes, ditches, and randomly placed obstacles.

Expanding Map: More props, improved textures, realistic tilesets, and extended world boundaries.

### 🔊 Audio & Visual Experience

Hit Sound Effects: Audio feedback on collisions.

Death Screen: A polished death screen with messages and effects.

Voiceovers: Character voice lines recorded for gameplay immersion.

Custom Assets: Many sprites created with LibreSprite, plus additional custom artwork.

---

## 🛠️ Tech Stack

Engine: Godot (GDScript)

Art: LibreSprite + custom assets

Audio: Custom-recorded voice lines & ambience

Platform: Windows & Linux support (via Godot export templates)

---

## 🚀 How to Run the Project

Follow these steps to run UniThon on your system using Godot.

### ✅ 1. Prerequisites

Make sure you have:

- Godot Engine (matching the version in project.godot)

- A computer running Windows, Linux, or macOS

- Basic understanding of running Godot projects

### ✅ 2. Clone the Repository

```powershell
git clone https://github.com/Sana-ai-coder/UniThon.git
cd UniThon
```

### ✅ 3. Open the Project in Godot

Launch Godot.

Click Import → Select the folder containing project.godot.

Godot will load all scenes, scripts, assets, and configurations.

### ✅ 4. Run the Game

Open the main scene (usually inside the scenes/ directory).

Click the Play ▶️ button in Godot.

### ✅ 5. Exporting (Optional)

To generate standalone executables:

Install Godot Export Templates.

Go to Project → Export.

Choose Windows/Linux → Export.

---

## 📂 Project Structure

UniThon/
├── assets/       # Sprites, tilesets, props, visuals
├── scenes/       # Game scenes (main scene, world, UI, menus)
├── scripts/      # GDScript files (player movement, spawners, collisions)
├── sounds/       # Hit sounds, ambience, voice lines
├── project.godot # Godot project config
├── icon.svg      # Game icon
└── README.md     # Documentation

---

## 📝 Developer Notes

Assets like props and characters are either created manually or contributed by teammates.

Voice lines are recorded for immersion and stored under sounds/.

Ambience music is sourced from YouTube — ensure proper attribution if distributing externally.

The game is updated frequently with map expansions, new hazards, and code optimizations.

---

## 🤝 Contributing

Fork the repository

Create a new branch

```powershell
git checkout -b feature/AmazingImprovement
```

Commit your changes

```powershell
git commit -m "Add new feature"
```

Push the branch

```powershell
git push origin feature/AmazingImprovement
```

Open a Pull Request

---

## 👨‍💻 Developed By

Sana-ai-coder & Team
Special thanks to contributors for assets, voice lines, and testing.
