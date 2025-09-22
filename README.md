# CodeAlpha_Hangmangame

# Hangman Game

This repository contains two implementations of the classic **Hangman Game**:

1. A **console-based version** (`hangman_game.py`)
2. A **GUI version** built with **Tkinter** (`hangman_gui.py`)

The game selects a random word from a word list (`word_file.py`, which you will need to provide) and challenges the player to guess the letters before running out of lives.


## Files in This Project

* **`hangman_game.py`**
  Console version of the game where players type letters into the terminal.

* **`hangman_gui.py`**
  GUI version using Tkinter with buttons, input fields, and visual hangman stages.

* **`hangman_stages.py`**
  Contains ASCII art representations of the hangman stages used in both game versions.

* **`word_file.py`** *(not included here, but required)*
  Must contain a Python list of words to be used in the game. Example:

  ```python
  words = ["python", "developer", "hangman", "challenge", "programming"]
  ```

---

## How to Run

### Console Version

```bash
python hangman_game.py
```

### GUI Version

```bash
python hangman_gui.py
```

---

## Requirements

* Python 3.x
* Tkinter (usually included with Python installations)

---

## Features

* Random word selection from a word list
* Visual representation of the hangman using ASCII art
* GUI version with reset functionality, input validation, and win/lose alerts
* Tracks guessed letters and remaining lives

---

## Future Improvements

* Add difficulty levels (easy, medium, hard)
* Expand the word list
* Implement score tracking

-
