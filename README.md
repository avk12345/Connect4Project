# Connect 4 (Java)
A two-player Connect 4 game implemented in Java with object-oriented design.

## Features
- Game board represented using a 2D array (6 rows × 7 columns by default).
- `dropPiece()` method simulates player moves and enforces gravity (pieces drop to lowest available row).
- Recursive `recWin()` algorithm checks for wins in **horizontal, vertical, and diagonal directions**.
- Includes methods for detecting full columns, resetting the board, and printing the board state.
- GUI components allow players to interact visually.
