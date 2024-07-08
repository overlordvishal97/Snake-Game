# Snake-Game
This project is a simple implementation of the classic Snake game using the Turtle graphics library in Python.

# Gameplay
The game starts with a snake at the center of the screen.
The user can control the snake using the arrow keys (Up, Down, Left, Right) or the WASD keys.
The goal is to eat the food (yellow circle) that appears randomly on the screen.
Each time the snake eats the food, it grows longer and the score increases.
The game ends when the snake collides with the wall or its own tail.
The high score is stored in a file and updated whenever a new high score is achieved.

# Code Organization
The code is organized into four files:
main.py: The main game loop and event handling.
food.py: The Food class, which represents the food that the snake eats.
scoreboard.py: The Scoreboard class, which displays the score and high score.
snake.py: The Snake class, which represents the snake and its movements.

# Features
User input for controlling the snake
Random food generation
Scorekeeping and high score tracking
Collision detection with walls and tail
Simple and easy to understand code

# Run the Game
To run the game, simply execute the main.py script. The Turtle graphics window will appear, and you can start playing!
