# FlappyBird

A simple Flappy Bird clone implemented in Java using Swing.

## Summary

**FlappyBird** is a Java-based game that emulates the popular Flappy Bird game using the Swing library. The objective of the game is to control a bird and navigate it through pairs of pipes without crashing into them. The game features simple controls, engaging gameplay, and a scoring system that tracks the player's progress.

## Description

**FlappyBird** is a classic arcade-style game where the player controls a bird attempting to fly through a series of obstacles. The game is implemented in Java and utilizes the Swing library for its graphical user interface. 

### Features:
- **Simple Controls**: The game uses the spacebar to control the bird’s movements.
- **Engaging Gameplay**: Players must navigate the bird through pairs of pipes, avoiding collisions to continue playing.
- **Scoring System**: The game tracks the player’s score based on the number of pipes successfully passed.

### How It Works:
- The bird continuously falls due to gravity.
- Pressing the spacebar makes the bird flap its wings and rise.
- The game places pairs of pipes at regular intervals, with gaps that the bird must fly through.
- The game ends if the bird collides with a pipe or falls out of the screen.

### Technical Details:
- **Graphics**: Custom images for the background, bird, and pipes.
- **Collision Detection**: The game checks for collisions between the bird and pipes to determine game over.
- **Timers**: The game uses timers to manage the game loop and pipe placement.

## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/SiddhiikaN/FlappyBird.git
   cd FlappyBird
