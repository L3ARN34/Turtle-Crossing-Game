# Turtle Crossing Game 🐢🚗

A classic 2D arcade game built in Python using the `turtle` graphics module. Guide your turtle safely across a busy highway, avoiding fast-moving cars, and score points by reaching the finish line!

## Table of Contents
- [Game Features](#game-features)
- [How to Play](#how-to-play)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Installation & Execution](#installation--execution)

---

## Game Features
- **Dynamic Difficulty:** Car speed increases with every level achieved.
- **Randomized Traffic:** Cars spawn continuously with randomized colors and positions along the y-axis.
- **Score Tracker:** Displays current level and game over notifications on screen.
- **Collision Detection:** Precise distance-based collision logic between the turtle and oncoming vehicles.

---

## How to Play
1. **Move Up:** Press the `Up Arrow` key to move your turtle forward.
2. **Goal:** Navigate through traffic to reach the top edge of the screen (`FINISH_LINE_Y = 280`).
3. **Winning Levels:** Reaching the top increases your level and speeds up traffic.
4. **Game Over:** Hitting any car stops the game instantly.

---

## Prerequisites
- **Python 3.x**: Ensure Python is installed on your local system.
- Standard Library Modules used (no extra `pip` installs required):
  - `turtle`
  - `random`
  - `time`

---

## Project Structure
```
Turtle-Crossing-Game/
│
├── main.py          # Main execution loop, screen setup, and key bindings
├── player.py        # Player class (turtle movement and reset logic)
├── car_manager.py   # Car generation, movement, and difficulty scaling
├── scoreboard.py    # On-screen level display and Game Over text
└── README.md        # Project documentation

Installation & Execution
Clone or download this repository:

Bash
git clone https://github.com/L3ARN34/Turtle-Crossing-Game.git
cd Turtle-Crossing-Game
Run the game:

Bash
python main.py
'''
