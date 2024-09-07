# TASK 4: Creating TIC TAC TOE App
# Overview
- As part of my initial assignment during the internship at Prodigy InfoTech, I developed a Python program that contains a simple implementation of the classic Tic Tac Toe game using Python and the Tkinter library for the graphical user interface (GUI).
# App Algorithm
The game algorithm is implemented in the TicTacToe class, which has the following key components:
- **Game State:** The game state is represented by a 3x3 grid of buttons, where each button represents a square on the grid. The game state is updated whenever a player makes a move.
- **Player Turn:** The game keeps track of whose turn it is, either "X" or "O".
- **Move Validation:** When a player makes a move, the game checks if the square is empty. If it is, the game updates the game state and switches the player turn.
- **Win Condition:** After each move, the game checks if there is a winner by examining all possible winning combinations (rows, columns, and diagonals). If a winner is found, the game ends and a message box is displayed to announce the winner.
- **Reset:** The game provides a reset button to restart the game.
# App Components
In the context of the Tic Tac Toe game, the following are the app components:
- Game Window: The main application window that contains the game grid and other UI elements.
- Game Grid: The 3x3 grid of buttons that represents the game board.
- Buttons: Each button on the game grid that can be clicked to make a move.
- Reset Button: A separate button that allows the player to reset the game.
- Message Box: A pop-up window that displays a message when the game is won or when an error occurs.
# Features
- 2-Player Game: The game allows two players, "X" and "O", to play against each other.
- 3x3 Grid: The game is played on a 3x3 grid, which is the traditional size for Tic Tac Toe.
- Alternating Turns: Players take turns marking a square on the grid, with "X" going first.
- Winning Conditions: The game checks for winning conditions after each move, including horizontal, vertical, and diagonal lines.
- Draw Condition: If all squares are filled and no player has won, the game is a draw.
# Requirements 
- Python 3.x
- Tkinter
