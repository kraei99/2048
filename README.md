Overview
This project is a Python implementation of the popular game 2048, using the Pygame library. The game is a single-player sliding tile puzzle where the objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048.


Requirements
Python 3.x
Pygame


Installation
Before running the game, ensure you have Python installed on your system. If not, you can download it from python.org. Additionally, you need to install Pygame, which can be done using pip:
pip install pygame


Running the Game
To start the game, simply run the Python script:
python 2048_game.py

Gameplay
Use the arrow keys (Up, Down, Left, Right) to move the tiles. When two tiles with the same number touch, they merge into one!

Features
Smooth animations and tile movement.
Score tracking and high score saving.
Game over screen with a restart option.
Game Rules
The game starts with two tiles, each with a value of either 2 or 4.
Every turn, a new tile will randomly appear in an empty spot on the board with a value of either 2 or 4.
Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid.
If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided.
The game is won when a tile with a number 2048 appears on the board.
The game is over when the player has no legal moves (no empty spaces and no adjacent tiles with the same value).
Customization
You can customize the game by modifying the source code. For example, you can change the grid size, colors, or even the winning condition.

High Score
The game saves the highest score achieved in a file named high_score. This score is displayed during the game and is updated if a new high score is reached.

License
This project is open-source and available under the MIT License.

Acknowledgements
This game is inspired by the original 2048 game created by Gabriele Cirulli.
Pygame library for providing the tools necessary to build this game.
