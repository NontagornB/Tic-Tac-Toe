# Tic-Tac-Toe Game
This is a simple Tic Tac Toe game implemented in Flutter. It allows players to play against each other or an AI opponent. The game supports grid sizes of 3x3, 4x4, and 5x5.

## Features
- Choose to play against another player or the AI
- Select grid size (3x3, 4x4, 5x5)
- Save game history for replay
- Display game board
- Check for a winner
- Display a dialog when the game ends

## Setup
1. Clone the repository: `git clone https://github.com/NontagornB/Tic-Tac-Toe.git`
2. Navigate to the project directory: `cd tic-tac-toe`
3. Run `flutter pub get` to install dependencies
4. Run `flutter run` to start the app on your device or emulator

## How to Play
- Select game settings (opponent and grid size) in the Settings screen
- Tap on a cell on the game board to make a move
- The game will alternate between players until there is a winner or a draw
- View game history on the Replay screen

## Design and Algorithm
- The game board is represented by a 2D array
- The AI opponent uses a simple algorithm to make moves:
    - If the AI can win in the next move, it will make that move
    - If the player can win in the next move, the AI will block that move
    - Otherwise, the AI will make a random move

