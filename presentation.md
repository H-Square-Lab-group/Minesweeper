# 🎮 Minesweeper (C++ with SFML)

An open-source clone of the classic **Minesweeper** game, built in **C++**. This project was forked and investigated as part of an academic assignment on open-source contributions and software analysis.

---

## 📌 Original Repository

Forked from: [https://github.com/jvanwinden/Minesweeper](https://github.com/jvanwinden/Minesweeper)

---

## 🧠 Project Overview

This Minesweeper game features a graphical interface with interactive gameplay. It includes features such as:
- Left/right click to reveal or flag tiles
- Grid-based mine generation and flood fill logic
- Game win/loss detection

The code is modular, beginner-friendly, and a great entry point for exploring GUI programming in C++.

---

## 🎯 Our Objectives

- Understand the structure, design, and flow of the project  
- Analyze the core modules and logic behind gameplay  
- Make a meaningful contribution (bug fix or feature addition)  
- Document the investigation and share our findings  

---

## 🧩 Project Structure
/Minesweeper
├── main.cpp         # Entry point for the game
├── game.h/.cpp      # Game logic and interaction controller
├── board.h/.cpp     # Board layout, mine generation, and logic
├── /res             # Image assets (tiles, UI, etc.)
├── /doc             # Documentation and diagrams

---

## 🔄 Game Flow (Simplified)

1. **main.cpp** initializes the game and handles user input.  
2. **Game class** processes moves and updates the board.  
3. **Board class** handles mine placement, recursive empty tile checking, and rendering.  
4. Game ends when player hits a mine or uncovers all safe tiles.  

---

## ✅ What We Learned

- How a modular C++ game project is structured  
- Integration of logic with graphical rendering (via SFML)  
- Recursive flood-fill implementation  
- Memory management and 2D dynamic arrays  
- Debugging compile-time issues like cyclic dependencies  
- Team collaboration on open-source codebases  

---

## 🛠️ Contribution Made
  
- Fixed a mine-counting bug in `Board::addToMinecount()`  
- Added input validation for board dimensions in `main.cpp`
- Fixed the header files to remove cyclic dependencies.

---

## ✍️ Authors

- Harshil  
- Yajat
- Het
  



