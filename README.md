Pokemon Card Matching Game

Game Overview

Memory Card Match challenges players to remember the locations of different cards on the board. The game consists of a grid of face-down cards, where players take turns flipping two cards at a time to find matching pairs.
Features:

A 4x5 grid of cards.
A variety of card types including "darkness", "double", "fairy", "fighting", "fire", "grass", "lightning", "metal", "psychic", and "water".
Tracks the number of errors made by the player.
Randomly shuffles the cards each time the game starts.

How to Play

Start the Game: Open the HTML file in your browser. The cards will be shuffled and displayed face-down.
Select Cards: Click on two cards to flip them over. If they match, they remain face-up; if they do not match, they will flip back after a short delay.
Track Errors: The game counts the number of mismatched attempts you make. Try to minimize your errors!
Win Condition: The game ends when all pairs have been matched.
Game Logic

The game operates as follows:
Initialization: Upon loading, the cards are shuffled and placed on the board.
Card Selection: Players can select cards by clicking them. The first selection is stored, and the second selection triggers a comparison.
Matching Logic: If both selected cards match, they stay face-up. If they do not match, they flip back after a brief pause, and the error count increments.
The core functions include:
shuffleCards(): Creates a shuffled deck of cards.
startGame(): Initializes the board and populates it with card images.
hideCards(): Hides all cards by displaying the back image.
selectCard(): Handles the logic for selecting cards and updating the game state.


Contributions to enhance the game are welcome! Please feel free to fork the repository, make your changes, and submit a pull request.
