# Icebreaker Game

A two-player strategy game developed using Python and the `graphics.py` library. The goal is simple: **move your player and break the ice to trap your opponent!**

---

## Project Overview

Icebreaker is a turn-based desktop game built for the CMPT 103 course at MacEwan University (Winter 2024). Two players take turns to move across a 6x7 grid and strategically break ice tiles to prevent the opponent from moving.

Each player can:
- Move one square in any direction 
- Break an ice tile after moving

The game ends when a player cannot make a move. The opponent is declared the winner.

---

## Features

- Splash screen with "Play Game" and "No Thanks" options
- Graphical user interface using `graphics.py`
- Turn-based logic with task switching (MOVE → BREAK ICE)
- Score tracking across multiple rounds
- Play new round and Quit options in-game
- Real-time player status updates

---

## How to Play

1. Launch the game
2. Click "Play Game"
3. Players take turns:
   - Move to an adjacent tile
   - Break one ice tile (except occupied or already broken)
4. The game ends when one player has no legal moves left
5. View scores and either continue to the next round or quit

---

## Project Structure

```
Icebreaker/
│
├── graphics.py          # Provided module for drawing windows and shapes
├── Muid's Stuff.py      # Main game logic (Icebreaker, Board, Player classes)
└── README.md            
```

---

## How to Run

1. Make sure you have Python installed 
2. Ensure `graphics.py` is in the same directory
3. Run the main game file:

```bash
python "Muid's Stuff.py"
```

---

## Screens & UI Elements

- **Splash Screen**: Game title and play/quit buttons
- **Game Board**: 6x7 grid with player pieces and ice
- **Score Screen**: View running scores between rounds

---

## Concepts Used

- Object-Oriented Programming
- GUI Programming with `graphics.py`
- Game loop logic and state tracking
- Coordinate translation from pixel to board
- Conditional rendering and user input handling

---

## Credits

**Author**: Abdulmuid Olaniyan  
**Course**: CMPT 103 – Winter 2024  
**Instructor**: Phillip Mees (inspiration for some methods like `in_rectangle`)

---

