
# Tic-Tac-Toe Game

This project is a simple implementation of the Tic-Tac-Toe game using Python. The game is played on a 3x3 grid, where two players take turns to place their marks (1 for player 1 and 2 for player 2). The first player to get three marks in a row, column, or diagonal wins the game. If all spots are filled and no player has three marks in a row, the game ends in a tie.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Game Logic](#game-logic)
- [Technologies Used](#technologies-used)

## Getting Started

### Prerequisites

Make sure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/).

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/nkululeko111/tic-tac-toe-game.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd tic-tac-toe-game
   ```

## Usage

1. **Run the game:**
   ```sh
   python tic_tac_toe.py
   ```

2. **Watch the game unfold:**
   - The game will display the board after each move.
   - The game pauses for 2 seconds between moves to simulate the turn-based play.
   - The game announces the winner at the end.

## Game Logic

- **Board Creation:** The game starts with an empty 3x3 board.
- **Possible Moves:** The game identifies all empty spots on the board.
- **Random Placement:** Each player randomly places their mark on an empty spot.
- **Win Check:** The game checks for a winning condition after each move.
  - **Row Win:** Checks if any row has the same mark.
  - **Column Win:** Checks if any column has the same mark.
  - **Diagonal Win:** Checks if either diagonal has the same mark.
- **Evaluation:** Determines if there is a winner or if the game ends in a tie.

## Technologies Used

- **Python**: The programming language used for the game logic.
- **NumPy**: Used for handling the game board as a 2D array.


