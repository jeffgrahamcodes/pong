# Pong Game

## Overview
This is a simple Pong game implemented in Python using the Turtle module. The game features two paddles and a ball, where two players can compete against each other to keep the ball in play and score points.

## Features
- Two-player gameplay
- Score tracking
- Ball movement with collision detection
- Paddle movement controls

## Requirements
- Python 3.x
- Turtle module (built-in with Python)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/jeffgrahamcodes/pong.git
   cd python-pong
   ```
2. Run the game:
   ```sh
   python main.py
   ```

## Controls
- **Left Paddle:**
  - Move Up: `W`
  - Move Down: `S`
- **Right Paddle:**
  - Move Up: `Up Arrow`
  - Move Down: `Down Arrow`

## Project Structure
- `main.py` - Initializes the game and manages the game loop.
- `paddle.py` - Handles paddle movement and positioning.
- `ball.py` - Manages ball movement and collision detection.
- `scoreboard.py` - Tracks and displays the score.

## How to Play
1. Start the game by running `main.py`.
2. Control the paddles using the assigned keys.
3. Try to hit the ball back and forth.
4. If the ball goes past a paddle, the opponent scores a point.
5. The game continues until you decide to exit.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Author
Created by jeffgrahamcodes. Contributions are welcome!

