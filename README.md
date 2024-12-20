# Snake Game

A simple Snake game built using Python and Pygame. The player controls a snake that grows longer as it eats fruit while avoiding walls and its own body. The game ends if the snake collides with the wall, its own body, or the boundaries of the game window.

## Features

- **Snake Movement**: Control the snake using arrow keys (Up, Down, Left, Right).
- **Fruit**: The snake eats fruit to grow longer and earn points.
- **Walls**: The game includes random wall segments that the snake must avoid. Every 3 fruits eaten, a new wall segment is added.
- **Game Over**: The game ends when the snake collides with the walls or its own body.
- **Score Display**: The score is displayed on the screen, and it increases when the snake eats fruit.
- **Game Restart**: After a game over, the game resets and you can continue playing.

## Installation

1. Make sure you have Python installed on your system (version 3.6 or higher).
2. Install Pygame by running the following command:

   ```bash
   pip install pygame

## Running the Game

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/gowthamee18/snake-game.git
   cd snake-game

2. Run the game by executing the following command:

   ```bash
   python main.py
   
The game window will open, and you can start playing.

##Controls
	•Use the arrow keys on your keyboard to control the snake:
	•Up Arrow: Move up
	•Down Arrow: Move down
	•Left Arrow: Move left
	•Right Arrow: Move right

##Gameplay
	•Objective: Eat the red fruit to grow the snake.
	•Avoid colliding with walls or the snake’s own body.
	•Every 3 fruits eaten will add a wall segment to the game area.

##Game Over
	•The game ends if the snake collides with the wall, its own body, or the boundaries of the game window.
	•After the game ends, the score is displayed, and the game will reset.
