<img src='.public/xo-logo.jpg' alt='logo tic-tac game' alt='Logo by Tic-Tac Game' width='50'/>

## Tic-Tac Game

This code represents the implementation of a tic-tac-toe game in React. It consists of various components and functions to manage the game. The file imports components such as GameBoard, Player, Log, GameOver, and an array named WINNING_COMBINATIONS, which contains all possible winning combinations in the game.

Players are represented by constants PLAYERS with symbols "X" and "O". The game board is initialized with the INITIAL_GAME_BOARD state, where all elements are set to null.

The code includes various functions to calculate the active player, player states, determine the winner based on the game rules, and check for a draw. The App component utilizes state to store information about players, current moves, and invokes corresponding event-handling functions.

The graphical interface of the game consists of a game container where players and the game board are located, along with the Log component displaying the move history. Additionally, upon game completion (win or draw), the corresponding GameOver component is displayed, indicating the winner and providing a button to restart the game.
