# Snake Game

This is a simple implementation of the classic Snake game using Python and the `tkinter` library.

## Game Description

In this game, you control a snake that moves around the window. The objective is to eat the food that appears randomly on the screen. Each time the snake eats the food, it grows longer, and your score increases. The game ends if the snake collides with the boundaries of the window or with itself.

## Features

- Simple graphics using `tkinter`
- Snake grows in length when it eats the food
- Score display
- Game over detection

## Requirements

- Python 3.x
- `tkinter` library (usually comes pre-installed with Python)

## How to Run

1. Make sure you have Python installed on your system.
2. Copy the `snake_game.py` file to your local machine.
3. Open a terminal or command prompt and navigate to the directory where `snake_game.py` is located.
4. Run the script using the following command:

   ```bash
   python snake_game.py

How to Play
Use the arrow keys to control the direction of the snake:
Left Arrow: Move left
Right Arrow: Move right
Up Arrow: Move up
Down Arrow: Move down
The snake will start moving in the direction it is facing. Change direction using the arrow keys to navigate the snake towards the food.
When the snake eats the food, it grows longer, and your score increases.
Avoid colliding with the boundaries of the window or the snake's own body, as this will end the game.
The game continues until the snake collides with the boundaries or itself, at which point the game over screen will be displayed.


Code Overview
Snake Class
The Snake class is responsible for creating and managing the snake's body. It initializes the snake's size and positions its initial coordinates.

Food Class
The Food class creates the food at random positions within the window. When the snake eats the food, a new food item is created.

Main Functions
next_turn(snake, food): Handles the snake's movement, collision detection, and food consumption.
change_direction(new_direction): Changes the snake's direction based on user input.
check_collisions(snake): Checks if the snake has collided with the boundaries or itself.
game_over(): Displays the game over screen.
UI Components
label: Displays the current score.
canvas: The main game area where the snake and food are drawn.
