Python Web Application - Snake

#### Video Demo: https://www.youtube.com/watch?v=3JkKUo7drXc 

#### Description:
The game Snake is a classic and well-known game in which the player controls a snake 
that moves around the screen, collecting fruit and avoiding obstacles. The goal of 
the game is to eat as much fruit as possible, causing the snake to grow longer and 
longer. The player must navigate the snake through the game field, avoiding running
into the walls or the snake's own body. If the snake collides with any of these 
obstacles, the game is over.

One of the files I wrote for this project is the Snake class, which handles the movement 
and growth of the snake. This class contains functions for moving the snake in different 
directions, checking for collisions with obstacles, and increasing the length of the snake 
when it eats fruit. Another file I wrote is the Game class, which handles the overall
gameplay and manages the game loop. This class contains functions for rendering the game 
field, checking for player input, and updating the game state.

One design choice I debated was how to handle the snake's movement. I considered using a
grid-based system, where the snake can only move to the cells immediately adjacent to 
its current position. However, I ultimately decided to use continuous movement, where the
snake can move to any position on the screen. This allows for smoother and more fluid
gameplay, but it also requires more complex collision detection.

