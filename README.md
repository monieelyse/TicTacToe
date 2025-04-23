# TicTacToe

# Tic-Tac-Toe Game

## Overview
This project implements a simple **Tic-Tac-Toe** game in C# using object-oriented programming principles. The game manages players, tracks moves, evaluates results, and notifies players when it's their turn.

## Features
- Two-player Tic-Tac-Toe gameplay.
- Dynamic board evaluation to determine winners or a draw.
- Event-driven notifications when the game ends or the next player is ready.
- Lightweight and easy-to-expand code structure.

## Game Mechanics
### Players
- There are two players: **X** and **O**.

### Board
- A **3x3** grid represents the game board.
- Each cell can be occupied by either `X` or `O`, or remain empty.

### Turns
- Players take turns placing their piece (`X` or `O`) on an empty board cell.
- If a move results in a win or a draw, the game ends.
- Otherwise, the next player is notified to take their turn.

### Win Conditions
A player wins when:
- They occupy an entire row.
- They occupy an entire column.
- They occupy a diagonal (either top-left to bottom-right or top-right to bottom-left).

If all cells are occupied and **no** win condition is met, the game results in a **draw**.

## How to Run
1. **Clone the repository** (or create your own C# project).
2. Ensure you have .NET installed.
3. Compile and run the project.

```sh
dotnet run
