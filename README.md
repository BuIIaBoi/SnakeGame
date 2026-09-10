# Snake Game

A classic Snake game built with Python's Tkinter — guide the snake around the board to eat food, grow longer, and avoid crashing into the walls or yourself.

## Features

- Arrow-key controls (Up, Down, Left, Right)
- Score tracking, displayed live above the board
- Snake grows by one segment each time it eats
- Collision detection for walls and self-collision, ending the game with a "GAME OVER" screen
- Direction locking prevents the snake from reversing directly into itself (e.g. you can't go left while already moving right)

## How to Run

Requires Python 3 with Tkinter (included in most standard Python installations — no extra packages to install).

```
python SnakeGame.py
```

## How to Play

Use the **arrow keys** to steer the snake toward the red food squares. Each one eaten adds a point and a segment to the snake's length. The game ends if the snake hits a wall or its own body.

## Project Structure

| File | Purpose |
|---|---|
| `SnakeGame.py` | Full game — window setup, snake/food logic, movement, collision detection, scoring |

## Known Limitations

- No restart button after "GAME OVER" — the script needs to be re-run to play again.
- No persistent high score between runs.

## Built With

- Python
- Tkinter
