# PingPong-game
A project that will explain some more JS for me.

A simple two-player Pong game built using vanilla JavaScript and the HTML5 Canvas API.
This project recreates the classic arcade experience: move the paddles, hit the ball, and score points!


## Features
- Two-player controls
- Real-time ball movement and collision detection
- Dynamic ball speed increase on paddle hits
- Score tracking and reset button
- Smooth rendering using requestAnimationFrame-style game loop (via setTimeout)


## How it works
The game uses the <canvas> element to render graphics.
JavaScript handles:
- Paddle and ball drawing
- Keyboard input
- Ball–paddle and wall collision detection
- Scoring and reset functionality


### The game loop repeatedly:
- Clears the board
- Draws paddles
- Moves the ball
- Checks collisions
- Updates the score if needed


## Controls
| Player                  | Move Up | Move Down |
|-------------------------|---------|-----------|
| Player 1 (Left Paddle)  | W       | S         |
| Player 2 (Right Paddle) | ↑       | ↓         |

Press the Reset button to restart the game.


## Technologies
- HTML5 & CSS3
- JavaScript


## Setup
1. git clone https://github.com/oliviaaMach/pingPong-game.git
Navigate to the project folder:
2. cd portfolio
3. Open index.html in your browser or run a local server (recommended for full JS functionality)


## Author
GitHub: https://github.com/oliviaaMach
