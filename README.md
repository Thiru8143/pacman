# Pac-Man Animation

This project is a simple animation of a Pac-Man character moving back and forth across the screen. The Pac-Man image alternates between open and closed mouth, and it changes direction when hitting the screen's edges.

## Technologies Used
- **HTML5**: Page structure.
- **CSS**: Styling the Pac-Man image.
- **JavaScript**: Handles the movement and animation logic for the Pac-Man.

## Features
- Pac-Man moves from left to right and back when hitting the screen boundaries.
- The image alternates between two frames (open and closed mouth) while moving.
- Pac-Man changes direction and the corresponding image is updated when it hits a wall.

## How to Use
1. Clone or download the repository.
2. Place the following images in the same directory as the `index.html` file:
   - `PacMan1.png` (Pac-Man facing right, open mouth)
   - `PacMan2.png` (Pac-Man facing right, closed mouth)
   - `PacMan3.png` (Pac-Man facing left, open mouth)
   - `PacMan4.png` (Pac-Man facing left, closed mouth)
3. Open the `index.html` file in any modern browser.
4. Click the "Start" button to begin the animation.

## Code Breakdown

- **HTML**: 
  - A button is used to start the animation. When clicked, it sets `isGameStarted` to `true` and makes the Pac-Man image visible.

- **CSS**: 
  - The Pac-Man image is styled using `position: absolute` to allow movement across the screen.

- **JavaScript**: 
  - The Pac-Man's position is updated by the `move()` function, which is triggered every 20 milliseconds using `setInterval`.
  - Pac-Man bounces back when it reaches the screen's boundaries.
  - The `imgMove()` function alternates the image between open and closed mouth frames every 200 milliseconds.
  - When Pac-Man changes direction, the image switches between the left-facing and right-facing frames.

## Installation
No installation is required. Simply ensure that the Pac-Man images are in the correct location and open the `index.html` file in a browser.

## Future Enhancements
- Add additional Pac-Man frames for smoother animation.
-
