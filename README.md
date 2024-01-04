# Frog Leap Puzzle Game 🐸🎮

## Overview

This script implements a text-based version of the Frog Leap puzzle game. The game involves moving frogs across a set of positions to solve the puzzle. The left set of frogs can only move right, and the right set of frogs can only move left. Frogs can move forward one space or jump two spaces by leaping over another frog from the opposite side. The puzzle is considered solved when the two sets of frogs have switched positions.

## Functions

### `display_game(positions)`

Displays the current state of the Frog Leap puzzle.

**Parameters:**
- `positions` (list): A list representing the positions of frogs and an empty leaf.

### `frog_leap_game()`

Implements the Frog Leap puzzle game logic.

#### Game Flow:

- Initializes the initial state of the puzzle with green ('G') and brown ('B') frogs.
- Enters an infinite loop where the game state is displayed, and the player is prompted to enter a move.
- Accepts user input and performs error checking.
- Checks the validity of the selected move and updates the game state accordingly.
- Checks for winning and losing conditions.
- Breaks out of the loop if the player quits, reaches the end of the game, or wins.

#### Input:

- User enters the position of the frog to move (0-6) or 'q' to quit.

#### Output:

- Displays the current state of the game after each move.
- Prints messages for invalid moves, reaching the end of the game, and winning.

## How to Play the Game:

1. Run the script to play the Frog Leap puzzle game.
2. Enter the position of the frog to move (0-6) or 'q' to quit. 🚀
