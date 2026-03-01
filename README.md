# Memory Game 

A console-based memory game developed in Python that challenges players to memorize and recall sequences of words, animals, colors, symbols, and complex terms across five progressively difficult levels.

## Author

**Luis Fernando Monjaraz Briseño**

## Project Team
- Monjaraz Briseño Luis Fernando
- Navarro Hernandez Diego Levy Absalon
- Navarro Rodriguez Damian
- Necoechea Solorzano Miguel Angel
- Nieves Toscano Oscar Yahir
- Olague Renteria Jorge Alexis Yahir

## Description

This memory game tests your ability to memorize and recall lists of items in order. Players start with 5 lives and must progress through 5 levels of increasing difficulty. Each level presents different types of content to memorize within a time limit.

## Features

- **Player Registration System**: Register and track multiple players
- **Lives System**: Start with 5 lives per game
- **Score Tracking**: Points are awarded based on level difficulty
- **Global Ranking**: View player scores and rankings
- **5 Difficulty Levels**: 
  - Level 1: Common words (60 seconds to memorize)
  - Level 2: Animals (60 seconds to memorize)
  - Level 3: Colors (45 seconds to memorize)
  - Level 4: Symbols (45 seconds to memorize)
  - Level 5: Complex medical/technical terms (30 seconds to memorize)

## Scoring System

- **Level 1**: 10 points
- **Level 2**: 10 points
- **Level 3**: 20 points
- **Level 4**: 20 points
- **Level 5**: 30 points

**Maximum Score**: 90 points

## How to Play

1. **Run the notebook** and select option 3 to play
2. **Enter your player name** (or register if new)
3. **Memorize the list** displayed on screen within the time limit
4. **Recall the items** in the exact order shown
5. **Progress through levels** or lose a life for incorrect answers
6. **Complete all 5 levels** without losing all lives to win

## Menu Options

1. **Register Player**: Add a new player to the game
2. **Check Scores**: View player statistics and global rankings
3. **Play**: Start a new game
4. **Exit**: Close the game

## Requirements

- Python 3.x
- IPython (for `clear_output()` function)
- Jupyter Notebook or compatible environment

## Installation

1. Clone this repository or download the notebook file
2. Ensure you have Python 3.x installed
3. Install required dependencies:
   ```bash
   pip install ipython
   ```
4. Open the notebook in Jupyter Notebook or JupyterLab
5. Run all cells to start the game

## Usage

```python
# Execute the main cell to start the game
# Select from the menu:
# 1 - Register a new player
# 2 - Check scores
# 3 - Play the game
# 4 - Exit
```

## Game Rules

- Players have **5 lives** at the start
- Each incorrect answer costs **1 life**
- Game ends when all lives are lost
- Lists must be recalled in **exact order** (except Level 5)
- Level 5 requires recalling **any one** item from the list
- Time limits decrease as difficulty increases

## Technical Details

- Built using Python dictionaries for player and score management
- Uses `time.sleep()` for timed memorization periods
- Console clearing with `IPython.display.clear_output()`
- Color-coded feedback (green for success, red for errors)

## Project

**Proyecto Final Equipo Escuadron lobo Xforce 69420 Doge**

## License

This project was developed as a final project for an educational course.

---

*Test your memory and climb to the top of the leaderboard!* 🏆
