# Flappy Bird in Python

A simple Flappy Bird clone built using Pygame.

## Features
- 3 Difficulty Levels: Easy, Medium, Hard (selectable on the welcome screen).
- High Score tracking (saved in `highscore.txt`).
- Background music and sound effects.
- Mouse click support for flapping and UI interaction.

## How to Run
1. Ensure you have Python installed.
2. Install Pygame: `pip install pygame`
3. Run the game: `python "flappy bird.py"`

## Asset Notice
**Important:** The `gallery` folder containing sprites and audio is excluded from this repository. To run the game, you must create a `gallery` folder in the project root with the following structure:
```
gallery/
  ├── audio/
  │   ├── die.wav
  │   ├── hit.wav
  │   ├── point.wav
  │   ├── swoosh.wav
  │   └── wing.wav
  └── sprites/
      ├── 0.png ... 9.png
      ├── background.png
      ├── base.png
      ├── bird.png
      ├── gameover.png
      ├── message.png
      └── pipe.png
```
You can generate the background music by running the script or adding your own `music.wav` to the `audio` folder.
