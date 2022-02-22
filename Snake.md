# Snake Game

Build your own "Snake" game (engine/API... UI not required, but a welcome bonus!). Ex: https://playsnake.org/
Please take a look at this link if you are unfamiliar with how the game works.

Please include the following features / constraints in your snake game:

- App has a gameboard, represented as an NxN matrix of "cells", always use an odd number for N so we can start the snake in the center of the board
- App gameboard has 3 sizes, small, medium, large which dictates the value N for the NxN gameboard
- When the game starts the snake begins moving
- Default direction of movement is North
- The game should use a timed interval to dictate the rate at which the snake moves across the board
- At any moment a new direction can be input which changes the direction in which the snake moves. N, W, E, S only.
- Snake moves around gameboard to consume a "food item" which exist on a "cell"
- One "food item" exists on the board at a time
- Snake has a length which indicates how many "cells" it takes up on the board
- The length of the snake is equal to the score of the user
- Snake grows by 1 "cell" each time it traverses over a "food item"
- If the Snake's body collides with any gameboard cells that are occupied by the snake it is game over
- The game should have 3 difficulties which indicate the rate at which the timed interval executes, Easy, Medium, Hard
- Persist the high score
- The game should have an API that supports the following features
- + change direction the snake is moving
- - start the game
- - pause the game
- - restart the game
- - adjust the difficulty
- - adjust the gameboard size
- - get the current length of the snake as a score
- - get the high score
- - get the current state of the board indicating what cells are empty, occupied by the snake, occupied by a "food item"
