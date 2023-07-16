# Snakegame-cpp
A simple snake game using graphics library as a part of end semester project of Programming Fundamentals.

The game is played in a graphical window, and the player controls the snake using arrow keys to eat food and grow longer. The objective is to eat as much food as possible without running into the walls or the snake's body.

Here's a brief explanation of the code:

1. The game starts with a main menu where the player can choose to start the game or view the instructions.
2. If the player selects the instructions option, the game displays the controls and how to play the game. Pressing the left arrow key returns to the main menu.
3. If the player chooses to start the game, the main game loop begins.
4. The snake moves in the direction of the arrow keys pressed by the player.
5. The snake's position is continuously updated, and the game checks for collisions with the walls or the snake's body.
6. When the snake eats food, its length increases, and the food is respawned at a new random position.
7. The game continues until the snake collides with the walls or itself, at which point it displays the player's score and the option to play again.

1. The `graphics.h` library used in this code is a non-standard library and may not be available in modern compilers. Therefore, you may need to use a compatible IDE or library to run this code.
2. The `readHighScore` and `writeHighScore` functions handle reading and writing the highest score from/to a file named "highscore.txt."
3. The game speed increases as the player eats more food, as the delay between each frame decreases.



