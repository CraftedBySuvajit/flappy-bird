# Flappy Bird in Python
Created by Suvajit Ghosh

A feature-rich Flappy Bird clone built using Pygame.

## ✨ Features
- **3 Difficulty Levels**: Easy, Medium, and Hard. Selectable via interactive buttons on the welcome screen.
- **Dynamic Speed & Gaps**: Each level adjusts the pipe speed and gap size for a tailored challenge.
- **High Score Tracking**: Saves your best score in `highscore.txt` so you can compete with yourself.
- **Sound System**: Background music and sound effects (flap, hit, score, swoosh).
- **Modern Controls**: Supports Mouse Clicks for flapping and UI interaction, as well as Space/Up keys.

## 🕹️ Controls
- **Mouse Left Click**: Flap / Select Level / Start Game
- **Space Bar / Up Arrow**: Flap

## 🚀 How to Run
1. Ensure you have Python installed.
2. Install Pygame: `pip install pygame`
3. Run the game: `python "flappy bird.py"`

## 📁 Asset Notice
**Important:** The `gallery` folder containing sprites and audio is excluded from this repository to keep it lightweight. To run the game, you must create a `gallery` folder in the project root with the following structure:
```
gallery/
  ├── audio/
  │   ├── die.wav
  │   ├── hit.wav
  │   ├── point.wav
  │   ├── swoosh.wav
  │   ├── wing.wav
  │   └── music.wav (or any custom background music)
  └── sprites/
      ├── 0.png ... 9.png
      ├── background.png
      ├── base.png
      ├── bird.png
      ├── gameover.png
      ├── message.png
      └── pipe.png
```
