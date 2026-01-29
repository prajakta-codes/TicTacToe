# Tic Tac Toe – Java Console Game

This is a simple **console-based Tic Tac Toe game** implemented in **Java** for two players.  
Players take turns entering their moves, and the program checks for a winner or a draw after every move.

---

## Features

- Two-player game (Player X and Player O)
- 3×3 game board
- Checks for:
  - Horizontal wins
  - Vertical wins
  - Diagonal wins
- Detects draw condition
- User-friendly console display
- Input validation for incorrect or already-filled positions

---

## How the Game Works

- The game board is a 3×3 grid.
- Player **X** starts the game.
- Players enter their move using **row and column format**:
  - Rows: `A`, `B`, `C`
  - Columns: `1`, `2`, `3`
- Example inputs:
  - `A1`
  - `B2`
  - `C3`

---

## Example Board Layout

X | O |



---

## Input Rules

- Input must be exactly **two characters**
- First character: `A`, `B`, or `C`
- Second character: `1`, `2`, or `3`
- Invalid or repeated moves will ask the player to try again

---

## Game End Conditions

- A player wins when they get **3 X’s or O’s in a row**
- The game ends with **"ITS A DRAW"** if all cells are filled and no one wins

---

## Concepts Used

- 2D Arrays
- Loops
- Conditional statements
- Methods
- User input using `Scanner`
- Basic game logic

---

## Author

Developed as a **Java practice project** to understand arrays, loops, and game logic.

---

## Possible Improvements

- Add replay option
- Improve UI formatting
- Add single-player mode with AI
- Add exception handling for input

