# Pac-Man WebGL

A simple Pac-Man inspired game built using plain JavaScript and the WebGL API. Play directly in your browser with no dependencies!

## Features

- Playable Pac-Man character, controlled by arrow keys.
- Ghost chases Pac-Man around the board.
- Eat all the dots to win the game.
- Pac-Man mouth animation.
- Game over screen when caught by the ghost.
- All rendering done with WebGL (no Canvas 2D or libraries).

## Demo

Open `pacman_webgl.html` in your browser to play.

## How to Run

1. **Download** or **clone** this repository.
2. Open `pacman_webgl.html` in any modern browser (Chrome, Firefox, Edge, Safari).
   - No build step or server required.
3. Enjoy the game!

> **Note:** Your browser must support WebGL. If you see "WebGL not supported", try updating your browser or enabling WebGL in your browser settings.

## Controls

- **Arrow Keys**: Move Pac-Man up, down, left, or right.

## Game Rules

- **Eat all the dots**: Collect all white dots to win.
- **Avoid the Ghost**: If the ghost touches Pac-Man, it's game over.
- The game restarts automatically on win or loss.

## Code Structure

- **HTML:** Single file, all code included in `<script>` block.
- **WebGL Rendering:** Uses vertex and fragment shaders for drawing circles (Pac-Man, ghost, dots).
- **Game Loop:** Handles updates, drawing, collision detection, and input.
- **No frameworks or dependencies**.

## Customization

- You can edit constants like `PACMAN_SPEED`, `GHOST_SPEED`, `NUM_DOTS`, or canvas size directly in `pacman_webgl.html` to tweak difficulty or appearance.

## Acknowledgements

- Inspired by the classic Pac-Man game.
- Built for educational and demonstration purposes.

---

Enjoy!
