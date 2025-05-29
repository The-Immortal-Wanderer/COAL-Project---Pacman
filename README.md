## 🟡 COAL Project - Pacman 🟡

A classic Pacman game recreated in MASM x86 Assembly, featuring multiple levels, colorful ASCII graphics, sound effects, player naming, and a variety of ghosts. Built for educational purposes and retro gaming fun!

---

### 📋 Table of Contents
1. Introduction
2. Features
3. Gameplay
4. How to Play
5. Controls
6. Game Over Conditions
7. Technical Details

---

### 🌟 Introduction

This project is a faithful recreation of the iconic Pacman arcade game, implemented in MASM x86 Assembly language. The game runs in a terminal/console window, using ASCII art for visual design, and provides an engaging retro experience. Players navigate through mazes, eat food pellets, avoid ghosts, and collect bonuses, with sound effects for added immersion.

---

### 🔥 Features

- **Multiple Levels:** Three unique maze layouts, each with custom wall and food placement.
- **Player Name Input:** Enter your name before starting; your score is associated with your name.
- **Colorful ASCII Graphics:** Uses bright color codes for walls, food, Pacman, ghosts, and menus.
- **Sound Effects:** Plays different sounds for game events (start, chomp, death, fruit, eat ghost).
- **Score and Lives Display:** Real-time display of score, lives (with hearts), and remaining food.
- **Five Ghosts:** Each ghost has its own character and starting position.
- **In-Game Menus:** ASCII-based main menu, instructions, game setup, pause, win, and loss screens.
- **Level Progression:** Advance to the next level after clearing all food on the current one.

---

### 🎮 Gameplay

- **Objective:** Clear each maze by eating all the food pellets ('.') while avoiding the ghosts ('G', 'H', 'O', 'S', 'T').
- **Movement:** Use arrow keys to guide Pacman ('C') through the maze.
- **Levels:** Three increasingly challenging mazes with different layouts and food counts.
- **Scoring:** Points are awarded for each food pellet and bonus fruit collected.
- **Lives:** Start with three lives (displayed as hearts). Lose a life if caught by a ghost.
- **Food & Bonuses:** Eat all pellets to advance; special symbols (like '@') may grant bonus points.
- **Ghosts:** Five ghosts patrol the maze, each with a unique character.

---

### 🕹️ How to Play

1. **Launch the Game:** Assemble and run the project in a 68k Assembly-compatible environment (see below).
2. **Enter Your Name:** Input your name when prompted.
3. **Navigate:** Use arrow keys to move.
4. **Eat Food:** Collect all '.' characters while avoiding ghosts.
5. **Survive:** Avoid ghosts to keep your lives.
6. **Progress:** Complete all levels to win.

---

### 🎯 Controls

| Key         | Action                   |
|-------------|--------------------------|
| Arrow Keys  | Move Pacman (Up/Down/Left/Right) |

---

### 🛑 Game Over Conditions

- **Victory:** All levels are cleared (all food eaten).
- **Defeat:** Lose all lives by getting caught by ghosts.
- **Final Score:** Displayed with your name after game ends.

---

### 🛠️ Technical Details

- **Language:** MASM x86 Assembly
- **Includes:** Uses `irvine32.inc` for basic I/O and console functions.
- **Sound:** Utilizes WAV files for classic Pacman sounds (beginning, chomp, death, fruit, eat ghost).
- **Graphics:** ASCII art for menus, instructions, levels, and in-game screens.
- **Variables:** Tracks player name, score, lives, level, ghost positions, and food count.
- **Structure:** Organized into data section (constants, variables, ASCII screens) and code section (drawing, input, game logic).
- **Custom Procedures:** For coloring, printing screens, moving Pacman, displaying ghosts, and handling input.

#### Sample Level Layout (ASCII Art)

The game features large, detailed ASCII screens for menus and levels, ensuring a visually engaging terminal experience.

---

### ▶️ Running the Game

1. **Requirements:**  
   - 68k Assembly environment (such as an emulator or assembler that supports `irvine32.inc` and Windows console).
   - Sound files: Ensure the required WAV files are present.
2. **Build & Run:**  
   - Assemble `Main.asm` using your assembler (e.g., MASM for x86).
   - Run the resulting executable in a compatible terminal.

---

### 🙏 Credits

Inspired by the classic Pacman arcade game.  
Developed as a COAL (Computer Organization and Assembly Language) course project.

---

### Screenshots

![Screenshot 2025-05-14 185307](https://github.com/user-attachments/assets/80af82ab-ba19-49e5-8d80-618c6dcb8918)

![Screenshot 2025-05-14 185335](https://github.com/user-attachments/assets/c25c38cb-ad31-4bb3-a4b2-2aa7f0b0903a)

![Screenshot 2025-05-14 185438](https://github.com/user-attachments/assets/302d9e53-4291-444e-acd2-884d05163bbd)

![Screenshot 2025-05-14 185502](https://github.com/user-attachments/assets/ae04c94a-e60f-4ee8-a2d8-a9a9a7f569bd)

![Screenshot 2025-05-14 225657](https://github.com/user-attachments/assets/ab51ce05-21f9-44ea-a05f-43d809e18aab)

![Screenshot 2025-05-14 225744](https://github.com/user-attachments/assets/be0d3cf7-9457-449a-a272-7777ce2764b0)

![Screenshot 2025-05-14 225803](https://github.com/user-attachments/assets/59fa1491-8778-487f-8950-be6d22718a37)

![Screenshot 2025-05-14 225840](https://github.com/user-attachments/assets/413c60fb-4141-4b06-9b4e-bd082d0d2970)

---
