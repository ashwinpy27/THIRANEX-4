# Tic Tac Toe Mini Game (C++)

A console-based, two-player Tic Tac Toe game built using C++.

## Features
- 3 x 3 game board displayed after every move
- Two players: X and O
- Players select positions using numbers 1 to 9
- Input validation prevents invalid and already occupied moves
- Win detection for rows, columns, and diagonals
- Draw detection
- Replay option after each game

## C++ concepts demonstrated
- Two-dimensional arrays
- `for` and `while` loops
- `if` / `else` conditional statements
- Functions
- Character variables
- Input validation

## Requirements
- C++ compiler (GCC / MinGW / Clang)
- C++11 or later

## Compile and run on Windows (MinGW)
Open a terminal in this folder:

```bash
g++ main.cpp -o TicTacToe
.\TicTacToe.exe
```

## Compile and run on Linux / macOS
```bash
g++ main.cpp -o TicTacToe
./TicTacToe
```

## How to play
1. Player X goes first.
2. Enter a number from 1 to 9 to place your symbol in that cell.
3. Players take turns.
4. The first player to get three symbols in a row, column, or diagonal wins.
5. If all nine cells are filled without a winner, the game is a draw.
6. Enter `y` to play another round or `n` to exit.

### Board position guide

```text
       1 | 2 | 3
      ---+---+---
       4 | 5 | 6
      ---+---+---
       7 | 8 | 9
```

This is an educational mini-game project. It is a local console game and does not require external libraries or internet access.
