# Pong Game - Classic Edition

This is a simple implementation of the classic Pong game, developed in C++ with retro-style animation. The game mimics the old-school illusion of motion by continuously clearing and redrawing the screen, making it a nostalgic experience for those familiar with early video games.

## Features

- **Two-Player Mode**: Compete with a friend in a 2-player setup.
  - Player 1 controls the left paddle using `W` (up) and `S` (down).
  - Player 2 controls the right paddle using `I` (up) and `K` (down).
  
- **Winning Conditions**: The first player to score 5 points wins the game.

- **Quit Option**: You can quit the game at any time by pressing `Q`.

- **Retro Aesthetics**: The game's animation style is based on clearing and redrawing the screen repeatedly, giving it an old-school vibe reminiscent of early arcade games. While this approach may cause some glitches, it adds to the charm of the classic experience.

## How to Play

1. Run the game and select your game mode (2 players).
2. Use the designated keys to control your paddles:
   - Player 1: `W` to move up, `S` to move down.
   - Player 2: `I` to move up, `K` to move down.
3. The goal is to prevent the ball from passing your paddle and score by bouncing it past your opponent.
4. The game ends when a player reaches 5 points or when the `Q` key is pressed to quit.

## Known Issues

- **Screen Flicker**: The game uses a simple approach to animation by clearing and redrawing the screen, which may result in noticeable flickering or glitches, adding to its retro charm.

## Future Improvements

- Refined graphics and smoother animations.
- AI-controlled paddle for single-player mode.
- Improved collision detection and more responsive controls.

Enjoy the nostalgic feel of classic Pong!
