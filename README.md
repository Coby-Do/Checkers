# Checkers Game

A simple checkers game implemented using JavaScript, HTML, and CSS. Play with a friend and experience a classic board game right in your browser!

# Languages and Tools:
<p align="left"> 
<a href="https://www.w3schools.com/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> 
</p>

## Features

- Two-player game
- Turn-based gameplay
- Simple rules
- Capturing opponent's pieces
- Kinging pieces upon reaching the opponent's side
- Win condition when all opponent's pieces are captured

## Getting Started

Clone this repository or download the files as a zip archive. Open the **CheckersV.html** file in your preferred browser to start playing.

## How to Play

1. Green player goes first.
2. Click on a piece to see the available moves.
3. Click on a highlighted cell to move the selected piece to that cell.
4. If a jump move is available, the player must take it.
5. After making a move, the turn goes to the other player.
6. When a piece reaches the opponent's side, it becomes a king, gaining the ability to move and capture backward.
7. The game ends when all pieces of one player are captured. The remaining player wins.

# Code Overview

## Functions

- **findPiece(pieceId)**: Finds the index of the given piece on the board.
- **givePiecesEventListeners()**: Adds click event listeners to the current player's pieces.
- **getPlayerPieces()**: Determines the current player's pieces and resets the board.
- **removeCellonclick()**: Removes the onclick attributes from all cells.
- **resetBorders()**: Resets the borders of all player pieces.
- **resetSelectedPieceProperties()**: Resets the selected piece properties to their default values.
- **getSelectedPiece()**: Gets the selected piece's ID and index on the board.
- **isPieceKing()**: Determines if the selected piece is a king.
- **getAvailableSpaces()**: Gets the available spaces for the selected piece to move.
- **checkAvailableJumpSpaces()**: Checks if the selected piece can jump over an opponent's piece.
- **checkPieceConditions()**: Checks if the selected piece is a king or not and adjusts its available moves accordingly.
- **givePieceBorder()**: Gives the selected piece a border if it has available moves.
- **giveCellsClick()**: Adds the onclick attribute to the cells where the selected piece can move.
- **makeMove(number)**: Moves the selected piece to the specified cell and updates the board.
- **changeData(indexOfBoardPiece, modifiedIndex, removePiece)**: Changes the board data and updates the piece state.
- **removeEventListeners()**: Removes the click event listeners from the current player's pieces.
- **checkForWin()**: Checks if the game is won by either player.
- **changePlayer()**: Changes the current player and updates the turn display.

# License

This project is released under the MIT License. Please see the 'LICENSE' file for more information.
