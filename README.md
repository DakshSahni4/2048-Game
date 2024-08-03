# 2048 Game

This repository contains a C++ implementation of the popular 2048 game.

## Overview

2048 is a single-player sliding tile puzzle game. The objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048.

## How to Play

- **Up Arrow**: Move tiles up
- **Down Arrow**: Move tiles down
- **Left Arrow**: Move tiles left
- **Right Arrow**: Move tiles right
- **ESC**: Quit the game

## Game Rules

1. **Moves**: Use arrow keys to move the tiles.
2. **Combine**: When two tiles with the same number touch, they merge into one.
3. **Win**: The goal is to create a tile with the number 2048.

## Code Structure

- **2048(1).cpp**: The main C++ file containing the game logic.

### Functions

- `void upmove(int a[4][4])`: Handles upward moves.
- `void downmove(int a[4][4])`: Handles downward moves.
- `void leftmove(int a[4][4])`: Handles leftward moves.
- `void rightmove(int a[4][4])`: Handles rightward moves.
- `void addblock(int a[4][4])`: Adds a new block randomly on the board.
- `void disp(int a[4][4])`: Displays the game board.
- `int check(int tmp[4][4], int a[4][4])`: Checks if the board has changed after a move.
- `int checkover(int a[4][4])`: Checks if there are any possible moves left.

## Compilation and Execution

1. **Compile**: Use the following command to compile the game.
    ```bash
    g++ -o 2048 2048(1).cpp
    ```
2. **Run**: Execute the compiled file.
    ```bash
    ./2048
    ```

## Screenshots




## Acknowledgments

- Inspired by Gabriele Cirulli's 2048 game.

