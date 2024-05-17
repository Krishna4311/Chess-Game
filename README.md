# Chess-Game

This repository contains a Python implementation of a two-player turn-based chess game. The game consists of the following files:

1. **chess.py**: This file contains the core logic of the chess game. It includes functions for determining legal moves, checking for checkmate and stalemate, handling pawn promotion, and more.

2. **gui.py**: This file contains the graphical user interface (GUI) elements for the chess game. It uses the Pygame library to draw the chessboard, pieces, and handle user interactions.

3. **main.py**: This file serves as the main entry point for the chess game. It initializes the game, handles user input, and updates the GUI based on game state changes.

4. Additionally, the repository includes an **images** directory containing images.

### How to Play:

1. **Setup**: download the **.py files** and store them in a folder.

2. **Installation**: Make sure you have Python and Pygame installed on your system.

3. **Starting the Game**: To start the game, run the `main.py` file using Python. This will launch the chess game interface.

4. **Gameplay**: The game is played by two players taking turns making moves. Click on a piece to select it, then click on a highlighted square to move the piece. If the move is legal, the piece will be moved to the new position. If the move is not legal, nothing will happen. Continue taking turns until one player wins by checkmate or the game ends in a stalemate.

5. **Promotion**: When a pawn reaches the opposite end of the board, a promotion choice will appear. Click on the desired piece to promote the pawn.

6. **End of Game**: The game ends when one player's king is checkmated, or when the game ends in a stalemate. If a player's king is in check, the corresponding message will be displayed on the screen.

---
