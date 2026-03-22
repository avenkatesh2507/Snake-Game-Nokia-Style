# Snake Game - Nokia Style

A classic Nokia-style Snake game implementation in Java featuring retro gameplay mechanics and graphics.

## Overview

This is a Java-based implementation of the iconic Snake game, inspired by the classic Nokia portable game that was popular in the early 2000s. Navigate the snake through the game board to eat food and grow longer while avoiding collisions with walls and yourself.

## Features

- **Classic Gameplay**: Navigate your snake around the board to collect food
- **Progressive Difficulty**: Game becomes more challenging as the snake grows
- **Retro Aesthetics**: Nokia-style visual design and gameplay mechanics
- **Score Tracking**: Keep track of your high scores
- **Simple Controls**: Easy-to-learn keyboard controls

## Requirements

- Java Development Kit (JDK) 8 or higher
- A terminal or IDE to compile and run the game

## How to Build

Compile the Java files:
```bash
javac GamePanel.java SnakeGame.java
```

## How to Run

Execute the game:
```bash
java SnakeGame
```

## Controls

- **Arrow Keys**: Move the snake (↑ ↓ ← →)
- **ESC**: Quit the game (if implemented)

## Game Rules

- Guide the snake to eat food pellets
- Each food eaten increases your score and snake length
- Avoid hitting the walls of the game board
- Avoid colliding with your own tail
- Game ends when you collide with a wall or yourself

## Project Structure

- `SnakeGame.java` - Main application entry point and window setup
- `GamePanel.java` - Game logic, rendering, and game state management

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to fork this repository and submit pull requests for any improvements!
