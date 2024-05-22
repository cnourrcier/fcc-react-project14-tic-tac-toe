# Tic Tac Toe

Part 14 of the freeCodeCamp 25 React Projects for interview.

This project is a simple implementation of the classic Tic Tac Toe game using React. The application features a 3x3 grid of squares that players can click to place their mark (X or O). 

Key functionalities include:

- Game State Management: Utilizes React's useState to handle the state of the squares, tracking which squares have been marked.

- Turn-Based Play: Alternates between X and O players, with isXTurn state determining the current player.

- Winner Determination: Checks for a winner after each move using the getWinner function, which compares the current board state against predefined winning patterns.

- Game Status Display: Updates the status message dynamically to show whose turn it is, if a player has won, or if the game is a draw.

- Game Reset: Includes a "Restart Game" button to reset the board and start a new game.