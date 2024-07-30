# Snake Game in C



## Overview

This project is a classic implementation of the Snake game in C, designed to run in the terminal. The game demonstrates key programming skills, including real-time input handling, dynamic display manipulation, and system programming techniques.

## Features

- **Terminal Control and ANSI Escape Codes**: Uses ANSI escape codes for cursor movement, screen clearing, and custom drawing.
- **Real-Time Input Handling**: Implements non-canonical mode and echo disabling for responsive gameplay.
- **Dynamic Data Management**: Manages snake's position and movement using arrays, efficiently updating the game state.
- **Game Logic Implementation**: Includes collision detection, random apple generation, and game-over conditions.
- **System Programming**: Utilizes `termios` for terminal attribute manipulation and `select` for non-blocking input handling.

[Game ScreenShot]
![image](https://github.com/user-attachments/assets/8da88b6c-2546-4522-a661-71d510939e9e)

## How to Run

1. **Compile the code**:
   ```sh
   gcc -o snake_game snake_game.c
   ./snake_game
