# Snake Game

Build your own "Snake" game engine/API...

Please take a look at this link if you are unfamiliar with how the game works. Ex: https://playsnake.org/

## Import Notes before getting started

- GUI is entirely optional
- Please do not use third party libraries without asking for approval. We want to see what fundamental tools and opinions you use to shape this project.
- API/Engine must be stand alone and clearly abstracted away from any client logic - Please do not combine this code with GUI logic, if you wish to include a GUI you may but do so such that it clearly lives in a separate layer
- Use of the term API is not intended to imply webserver/REST functionality ETC

## Please include the following features / constraints in your snake game:

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
- The game should have an external facing API that supports the following features
- - change direction the snake is moving
- - start the game
- - pause the game
- - restart the game
- - adjust the difficulty
- - adjust the gameboard size
- - get the current length of the snake as a score
- - get the high score
- - get the current state of the board indicating what cells are empty, occupied by the snake, occupied by a "food item"
- If you have any gaps, omissions, areas needing improvement or otherwise interesting & relevant thoughts please document them in a file named "Notes"
