# tictactoe
C++ game

It's a well-structured Tic-Tac-Toe game that allows a human player to play against a computer opponent.

Key features:

- Clear organization: The code is divided into functions for different tasks, making it easier to understand and maintain.
- Computer opponent: The Computer uses the Minimax algorithm to make strategic moves, ensuring a challenging opponent for the human player.
- User-friendly interaction: The game provides clear instructions and prompts, guiding the player through the game.
- Error-handling: The code includes checks for invalid inputs and occupied positions, preventing unexpected errors.
- Draw detection: The game recognizes when the board is full and no winner has been determined, declaring a draw.
- Multiple games: The player can choose to play multiple games in a row without restarting the program.

Essential functions:

- showBoard: Displays the current state of the Tic-Tac-Toe board.
- showInstructions: Provides instructions on how to play the game.
- initialise: Sets up the board with empty cells at the beginning of the game.
- declareWinner: Announces the winner (either the computer or the human) when the game ends.
- rowCrossed, columnCrossed, diagonalCrossed: Check for winning conditions by examining rows, columns, and diagonals.
- gameOver: Determines if the game has ended (either with a winner or a draw).
- minimax: Implements the Minimax algorithm for the Computer's decision-making.
- bestMove: Finds the best possible move for the computer based on the Minimax algorithm.
- playTicTacToe: Manages the gameplay, alternating turns between the computer and the human player.
- main: The main function that handles the overall game flow, including starting the game, prompting the player for choices, and continuing or quitting the game.
