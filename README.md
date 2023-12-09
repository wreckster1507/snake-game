# Snake Game

This is a simple implementation of the classic Snake Game using HTML, CSS, and JavaScript. The game is played on a grid, where the player controls a snake that moves around the board, eats food, and grows longer. 
The goal is to achieve the highest score by collecting as much food as possible without colliding with the boundaries of the board or the snake itself.

## Getting Started

To run the game, simply open the HTML file in a web browser. You can control the snake using the arrow keys (Up, Down, Left, Right) and start the game by pressing the Spacebar.

## Game Features

### Game Elements

- Snake: The player controls a snake that consists of connected segments. The snake grows longer each time it consumes food.

- Food: Represented by a colored cube, food appears randomly on the board. When the snake collides with the food, it eats it, grows longer, and the player scores points.

### Controls

- Arrow Keys: Change the direction of the snake (Up, Down, Left, Right).

- Spacebar: Start the game. If the game is not running, pressing Spacebar will start it.

### Game Over

The game ends if the snake collides with:

- Board Boundaries: If the snake goes beyond the boundaries of the game board.

- Itself: If the snake collides with its own body.

## Code Structure

The code is organized into several functions, each responsible for a specific aspect of the game. Here's an overview of the key functions:

- draw(): Draws the game map, snake, and food on the board.

- move(): Moves the snake in the current direction. Handles collisions with food, updates the score, and adjusts the game speed.

- startGame(): Initiates the game by hiding instructions and starting the game loop.

- handleKeyPress(event): Listens for key presses to change the snake's direction or start the game.

- checkCollision(): Checks for collisions with board boundaries or the snake itself, triggering a game reset if necessary.

- resetGame(): Resets the game to its initial state, updating the high score and stopping the game loop.

- increaseSpeed(): Increases the game speed as the snake eats more food.

- updateScore(): Updates the displayed score on the screen.

- stopGame(): Stops the game loop and displays the instructions and logo.

- updateHighScore(): Updates the high score if the current score surpasses the previous high score.
