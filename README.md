# Sonic2D

A 2D platformer game inspired by Sonic, developed in C++ using custom graphics and input handling. The game features multiple levels, scoring, collision detection, and music/sound effects.

## Features

- **Multiple Game States:** Menu, gameplay, high score, help, about, settings, pause, win, and game over screens.
- **Levels:** Includes at least two playable levels with unique obstacles and enemies.
- **Scoring System:** Collect rings, balls, and food to increase your score. High scores are saved and displayed.
- **Collision Detection:** Handles collisions with obstacles, enemies, and collectibles.
- **Character Controls:** Move Sonic left/right, jump, and interact with the environment using keyboard and special keys.
- **Music & Sound:** Background music and sound effects with options to toggle on/off.
- **Custom Graphics:** Uses bitmap images for backgrounds, menus, and sprites.

## Installation

1. **Requirements:**
   - Visual Studio 2022 or compatible C++14 compiler.
   - Windows OS (uses WinAPI for sound).
   - All image and sound assets in the `images` and `bgrand` folders.

2. **Build Instructions:**
   - Open the solution in Visual Studio.
   - Ensure all required header files and assets are present.
   - Build and run the project.

## Usage

- **Start the Game:** Run the executable. The main menu will appear.
- **Controls:**
  - **Arrow Keys:** Move Sonic Jump (Up).
  - **Mouse:** Navigate menus and select options.
  - **Keyboard:**
    - `1`: Play Level 1 music
    - `2`: Play alternate music
    - `0`: Stop music
    - `p`: Pause game (during gameplay)
    - `END`: Exit game
    - `HOME`: Return to main menu

## File Structure

- `iMain.cpp`: Main game loop, state management, input handling.
- `Collision.h`, `Score.h`, `Level1.h`, `Level2.h`: Game logic for collisions, scoring, and levels.
- `iGraphics.h`, `bitmap_loader.h`: Graphics and image loading utilities.
- `images/`, `bgrand/`: Asset folders for images and backgrounds.

## Credits

Inspired by classic Sonic games.

## License

This project is for educational and non-commercial use only.  
All assets are property of their respective owners.

