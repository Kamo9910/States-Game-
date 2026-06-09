# 🗺️ U.S. States Game

A geography guessing game built in Python using `turtle` and `pandas`. Type the name of a U.S. state and it appears in the correct location on the map. See how many of the 50 states you can name!

## Features

- Interactive U.S. map displayed using the `turtle` graphics module
- Type state names and they appear at the correct coordinates on the map
- Tracks the number of correctly guessed states
- When you quit, a CSV file is generated listing all the states you missed — so you can study and improve

## How to Run

**Requirements:** Python 3.x with `pandas` installed.

```bash
pip install pandas
python main.py
```

## How to Play

1. A blank U.S. map appears on screen
2. A prompt asks you to guess a state name
3. Type a correct state name and it will appear on the map
4. Type `Exit` to quit — a `states_to_learn.csv` file will be saved with all missed states

## Project Structure

```
us-states-game/
│
├── main.py                  # All game logic in a single script
├── blank_states_img.gif     # U.S. map image used as the turtle background
└── 50_states.csv            # CSV file with state names and x/y coordinates
```

## Output

When you exit the game, a file is automatically saved:

```
states_to_learn.csv    # List of states you did not guess correctly
```

Use this file to study the states you missed and try again!

## About

Built as part of **Dr. Angela Yu's 100 Days of Code: The Complete Python Pro Bootcamp**. This project covers working with `pandas` DataFrames, reading CSV files, and combining data with `turtle` graphics for an interactive experience.
