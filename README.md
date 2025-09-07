# Tic-Tac-Toe AI with Minimax Algorithm

A C++ implementation of a Tic-Tac-Toe game where the player competes against an AI powered by the **Minimax algorithm**. The AI always plays optimally and is impossible to beat.
## Features
- Play as either **X** or **O**.
- AI uses **Minimax algorithm** with optimal decision-making.
- Fully interactive console-based interface.
- Supports both **AI-first** and **Human-first** modes.
## How It Works
- Each cell on the board is represented as:
  - `2` → Empty
  - `3` → X
  - `5` → O

- The winner is determined by checking the product of values in winning lines:
  - \( 3 \times 3 \times 3 = 27 \) → X wins
  - \( 5 \times 5 \times 5 = 125 \) → O wins

- The AI uses **minimax** to evaluate every possible game state recursively and selects the move that maximizes its chances of winning.
## Complexity
**Time Complexity (Worst Case):** `O(9!)` (≈ 362,880 game states)  
**Space Complexity:** `O(1)` (only 10 board positions and a recursion depth of at most 9)



