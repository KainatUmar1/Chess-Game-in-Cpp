# Chess Project

# Overview
Welcome to the Chess Game Project! This project is designed to provide a comprehensive and engaging chess-playing experience, featuring various advanced functionalities to enhance gameplay. Developed using `SFML (Simple and Fast Multimedia Library)`, the game includes essential chess mechanics and additional features such as pawn promotion, highlighting legal moves, and check/self-check detection.

# Features
## 1. SFML Integration:
The game utilizes SFML for rendering graphics, handling input, and managing window operations. SFML ensures smooth and visually appealing gameplay with responsive controls and animations.

## 2. Pawn Promotion:
When a pawn reaches the opponent's back rank, it is promoted to a more powerful piece (Queen, Rook, Bishop, or Knight). This feature allows players to choose the desired piece for promotion, adding strategic depth to the game.

## 3. Highlighting Legal Moves:
To assist players in making informed decisions, the game highlights all legal moves for the selected piece. This feature ensures clarity and helps prevent illegal moves, making the game accessible to players of all skill levels.

## 4. Check Detection:
The game detects when a player's king is in check. This crucial feature alerts the player to take immediate action to protect their king, maintaining the integrity of the game's rules.

## 5. Self-Check Prevention:
The game prevents players from making moves that would place their own king in check. This feature enforces the rules of chess, ensuring that all moves are legal and valid.

# Code Structure
The project is organized into several header and C++ source files, each handling different aspects of the game. The implementation of core logics are divided in the following main files:
- **Bishop.cpp**: Implementation of the Bishop piece's movement and behavior.
- **Board.cpp**: Manages the game board, including piece placement and move validation.
- **Chess Game.cpp**: The main file where the game is initialized and run.
- **Chess.cpp**: Contains core game logic and overall game management.
- **King.cpp**: Implementation of the King piece's movement and check detection.
- **Knight.cpp**: Implementation of the Knight piece's movement and behavior.
- **Pawn.cpp**: Handles pawn-specific behavior, including movement and promotion.
- **Piece.cpp**: Base class for all chess pieces, defining common attributes and methods.
- **Player.cpp**: Manages player-specific data and actions.
- **Queen.cpp**: Implementation of the Queen piece's movement and behavior.
- **Rook.cpp**: Implementation of the Rook piece's movement and behavior.
- **Utility.cpp**: Contains utility functions and helper methods used throughout the game.

# How to Play
1. **Run the Game**: Compile and run the Chess Game.cpp file to start the game.
2. **Select a Piece**: Click on a piece to see its legal moves highlighted on the board.
3. **Make a Move**: Click on a highlighted square to move the selected piece.
4. **Promotion**: If a pawn reaches the opposite end of the board, choose the piece for promotion.
5. **Check Alerts**: Pay attention to check notifications and make necessary moves to safeguard your king.
6. **Enjoy the Game**: Continue playing until a checkmate, stalemate, or draw occurs.

# Conclusion
The Chess Game Project aims to provide a complete and enjoyable chess experience with advanced features that both beginners and experienced players will appreciate. We hope you enjoy playing this game as much as we enjoyed developing it!

# Author
- **Kainat Umar** - *Developer of this `Chess Game Project in CPP` utilizing the power of OOP principles and SFML library.*
