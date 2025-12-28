# Yahtzee On Terminal

A Python terminal game that mimics the board game **Yahtzee**.  
This project focuses on core Python fundamentals like **functions** and control flow (**while** loops and **for** loops), and uses **pandas** for score handling.

---

## Install

```bash
pip install Yahtzee-On-Terminal==0.0.3
```

---

## How to Launch the Game

Right now, the game is launched from inside a Python session (not as `python -m ...`).

### 1) Start Python in your terminal

```bash
python
```

or

```bash
python3
```

### 2) Import the game entry point

```python
from yahtzee_on_terminals import main
```

### 3) Start the game

```python
main.main()
```

---

## How to Play (In-Game Flow)

At a high level, Yahtzee works like this:

1. **Roll dice**  
   You roll a set of dice at the start of your turn.

2. **Choose which dice to keep**  
   After seeing the roll, you decide which dice you want to keep.

3. **Reroll the rest (limited rerolls)**  
   You can reroll the dice you didn't keep, up to the game's allowed number of rerolls for that turn.

4. **Pick a scoring category**  
   When you're done rolling, you select a scoring category to apply that roll to (for example: three-of-a-kind, full house, etc.).

5. **Score is recorded and the game continues**  
   The score is added to your score sheet, and the game proceeds until all categories/rounds are filled.

> Exact prompts and inputs are shown during gameplay in the terminal.

---

## Requirements

- Python 3.x
- `pandas` (installed automatically when you install the package)

---

## Features

- Dice rolling + rerolling flow
- Turn-based loop structure (rounds/turns)
- Scoring logic implemented with Python functions
- Score tracking / organization using `pandas`

---

## Troubleshooting

### ImportError / ModuleNotFoundError
If `from yahtzee_on_terminals import main` fails, it usually means the package was installed into a different Python environment than the one you're running.

Try installing with the same interpreter:

```bash
python -m pip install Yahtzee-On-Terminal==0.0.3
```

or

```bash
python3 -m pip install Yahtzee-On-Terminal==0.0.3
```

Then start that same `python` / `python3` again and retry the import.

---

## License

MIT License - see LICENSE for details.

---

## Credits

Inspired by the board game Yahtzee.

## Contact
lhirasaw@usc.edu
For questions or feedback, feel free to reach out!
