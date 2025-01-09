# Tic Tac Toe

This is a simple command-line implementation of the classic game Tic Tac Toe for two players.

## How to Play

1. **Setup**: The game board is a 3x3 grid initialized with empty spaces.
2. **Players**: Two players take turns, one as 'X' and the other as 'O'.
3. **Input**: Players input the row and column numbers (0, 1, or 2) to place their mark on the board.
4. **Winning**: A player wins by placing three of their marks in a horizontal, vertical, or diagonal row.
5. **Draw**: The game ends in a draw if all cells are filled without a winner.

## Functions

- `print_board(board)`: Displays the current state of the board.
- `check_winner(board, player)`: Checks if the specified player has won.
- `is_draw(board)`: Checks if the game is a draw.
- `tic_tac_toe()`: Main function to run the game.

## How to Run

1. Clone the repository or copy the code into a Python file (e.g., `tic_tac_toe.py`).
   ```bash
   git clone https://github.com/shivamr021/tic-tac-toe.git
   ```
2. Run the file using Python:
   ```
   python tic_tac_toe.py
   ```
3. Follow the on-screen instructions to play the game.

## Example Gameplay

```
   |   |  
----------
   |   |  
----------
   |   |  
Player X, enter the row (0, 1, 2): 0
Player X, enter the column (0, 1, 2): 0
X |   |  
----------
   |   |  
----------
   |   |  
Player O, enter the row (0, 1, 2): 1
Player O, enter the column (0, 1, 2): 1
X |   |  
----------
   | O |  
----------
   |   |  
...
```

## Requirements

- Python 3.x

## Author

Shivam Rathod
