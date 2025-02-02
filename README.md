# Tic-Tac-Toe-Game_Project
script.js
This file contains the JavaScript logic for the Tic-Tac-Toe game.

Functions and Event Listeners
#resetGame
This function resets the game state:

  Sets the turn to player O.
  Resets the move count.
  Enables all the boxes.
  Hides the message container.
Event Listener for Boxes
Each box in the game grid has an event listener that:

  Logs a message to the console when a box is clicked.
  Sets the box text to "O" or "X" depending on the current player's turn.
  Disables the clicked box to prevent further clicks.
  Increments the move count.
  Checks for a winner after each move.
  Calls the gameDraw function if all boxes are filled and there is no winner.

Description
  resetGame Function: Resets the game state, enabling all boxes and hiding the message container.
  Box Event Listener: Handles player moves, updates the box text, disables the box, increments the move count, checks for a winner, and handles a draw scenario.
  This file provides the core functionality for the Tic-Tac-Toe game, managing player turns, checking for a winner, and handling game resets.  
