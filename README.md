## 🎮 Tic Tac Toe (C Program)

A simple Tic Tac Toe game implemented in C language for two players.
This game is played in the terminal/command prompt and follows the standard 3x3 Tic Tac Toe rules.

## 📌 Features

Two-player mode (Player 1 = X, Player 2 = O)

Board is displayed after each turn

Input validation (prevents overwriting existing moves and invalid choices)

Automatically detects win, draw, or continues the game

Works on Windows (uses system("cls") to clear the screen)

## 🛠️ How It Works

The game board is represented by a character array:
```bash
char square[10] = { '0','1','2','3','4','5','6','7','8','9' };
```
Players take turns entering a number (1–9) corresponding to the board position.

The checkWin() function checks for win conditions or draw.

The drawBoard() function displays the current board in a neat format.

## 🚀 Getting Started
1. Clone or Download

Save the code in a file, e.g. tic_tac_toe.c.

2. Compile

Using GCC:
```bash
gcc tic_tac_toe.c -o tic_tac_toe
```
3. Run
```bash
./tic_tac_toe
```
## 🎯 Example Gameplay
```bash
Tic Tac Toe
Player 1 (X)  -  Player 2 (O)

     |     |     
  1  |  2  |  3  
---------------------
     |     |     
  4  |  5  |  6  
---------------------
     |     |     
  7  |  8  |  9  
     |     |     

Player 1 (X), enter the choice (1-9): 5
```
The board updates after each move until a winner is found or the game ends in a draw.
## 📂 File Structure
```bash
tic_tac_toe.c   # Main C source code
README.md       # Project documentation
```
## 📝 Notes

The code uses system("cls") which works on Windows.

For Linux/macOS, replace it with:
```bash
system("clear");
```

This is a console-based game with no AI (only 2 players).

## 📌 Future Improvements

Add single-player mode with a simple AI.

Improve UI with colors (using ANSI escape codes).

Allow replay option without restarting the program.

## 👨‍💻 Author

Developed as a simple C programming project to practice arrays, conditionals, and loops.


