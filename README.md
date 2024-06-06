# Snake-game

---

# Snake Game with Python and Pygame

This is a classic Snake game implemented in Python using the Pygame library. The game features end-to-end functionality with graphical elements, sound effects, and a highscore tracking system.

## Features

- **Classic Snake Gameplay:** Move the snake to collect apples and grow longer.
- **Graphics:** Custom graphics for the snake's head, body, and tail, as well as the apple.
- **Sound Effects:** Background music and sound effects for eating apples and crashing.
- **Highscore Tracking:** Keeps track of the highest score achieved.
- **Pause and Resume:** Pause the game with the spacebar and resume it at any time.
- **Game Over Screen:** Displays the player's score when the game ends.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/anishvedant/snake-game.git
   cd snake-game
   ```

2. **Install Dependencies:**
   Ensure you have Python and Pygame installed. You can install Pygame using pip:
   ```bash
   pip install pygame
   ```

3. **Add Game Assets:**
   Place the required graphic and sound files in the appropriate directories:
   - `Graphics/head_up.png`
   - `Graphics/head_down.png`
   - `Graphics/head_right.png`
   - `Graphics/head_left.png`
   - `Graphics/tail_up.png`
   - `Graphics/tail_down.png`
   - `Graphics/tail_right.png`
   - `Graphics/tail_left.png`
   - `Graphics/body_vertical.png`
   - `Graphics/body_horizontal.png`
   - `Graphics/body_tr.png`
   - `Graphics/body_tl.png`
   - `Graphics/body_br.png`
   - `Graphics/body_bl.png`
   - `Graphics/apple.png`
   - `Sound/crunch.wav`
   - `Sound/crash.mp3`
   - `Sound/music.mp3`
   - `Font/PoetsenOne-Regular.ttf`

## Usage

1. **Run the Game:**
   ```bash
   python snake.py
   ```

2. **Gameplay Instructions:**
   - Use the arrow keys to control the direction of the snake.
   - Press `SPACE` to pause and resume the game.
   - Press `ESC` to quit the game.

## Game Mechanics

### Snake Movement

The snake is controlled using the arrow keys:
- `UP`: Moves the snake up (if it's not currently moving down).
- `RIGHT`: Moves the snake right (if it's not currently moving left).
- `DOWN`: Moves the snake down (if it's not currently moving up).
- `LEFT`: Moves the snake left (if it's not currently moving right).

### Growing the Snake

When the snake eats an apple, it grows by one block. The position of the next apple is randomized within the game grid.

### Collision Detection

The game ends if:
- The snake collides with the walls (edges of the game window).
- The snake collides with itself.

### Highscore Tracking

The game tracks the highest score achieved and displays it on the screen. The highscore is saved in a `highscore.txt` file.

### Sound Effects

- **Background Music:** Loops continuously during the game.
- **Crunch Sound:** Plays when the snake eats an apple.
- **Crash Sound:** Plays when the game ends due to a collision.

## Code Structure

- `snake.py`: Main game file containing all the game logic and functions.
- `Graphics/`: Directory containing the image assets for the game.
- `Sound/`: Directory containing the sound effects and background music.
- `Font/`: Directory containing the font file used in the game.

## Future Improvements

- Add more levels with increasing difficulty.
- Implement different game modes (e.g., time attack, endless mode).
- Enhance graphics and animations.
- Add more sound effects and background music tracks.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests with your improvements and bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Disclaimer

This game is for educational purposes and personal enjoyment. Ensure you have the appropriate rights to use the graphic and sound assets included in the game.

---
