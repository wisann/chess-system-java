# Chess Game

This is a Java implementation of the classic game of chess. The program allows two players to play chess on the command line interface (CLI). The game follows the standard rules of chess.

## Features

- Player vs Player: The game supports two-player mode, where two human players can play against each other.
- Check and Checkmate: The game detects check and checkmate situations and notifies the players accordingly.
- Valid Moves: The program validates the moves made by the players and ensures they follow the rules of chess.
- Piece Promotion: If a pawn reaches the opposite end of the board, the player can promote it to another piece (bishop, knight, rook, or queen).
- En Passant: The program supports the en passant capture rule.
- Castling: The program supports the castling move.

## Getting Started

To run the chess game, follow these steps:

1. Ensure you have Java Development Kit (JDK) installed on your system.
2. Clone this repository to your local machine.
3. Compile the Java files using the following command:
```shell
javac *.java
```

4. Run the program using the following command:
```shell
java Program
```

## How to Play

1. After starting the program, the initial chessboard will be displayed.
2. Enter the source position of the piece you want to move (e.g., "e2").
3. Enter the target position to move the piece to (e.g., "e4").
4. If the move is valid, the program will update the board and display it.
5. Continue making moves until the game ends.

Note: When promoting a pawn, enter the desired piece type (B, N, R, or Q) when prompted.

## Project Structure

- `Program.java`: Main class that contains the program's entry point.
- `UI.java`: User interface class responsible for handling input/output and displaying the game on the CLI.
- `Board.java`: Class representing the chessboard and its operations.
- `BoardException.java`: Custom exception class for board-related exceptions.
- `Piece.java`: Abstract class representing a chess piece and its common attributes and methods.
- `Position.java`: Class representing a position on the chessboard.
- `ChessMatch.java`: Class representing a chess match and managing the game logic.
- `ChessException.java`: Custom exception class for chess-related exceptions.
- `ChessPiece.java`: Class representing a chess piece and its specific attributes and methods.
- Other classes: Additional classes representing specific chess pieces (Pawn, Rook, Knight, Bishop, Queen, King).



