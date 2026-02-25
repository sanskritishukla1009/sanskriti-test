# 🐍 Snake Game

A classic Snake game built with vanilla JavaScript and HTML5 Canvas.

## File

```
sanskriti-test/snake.html
```

## How to Play

Open `snake.html` in any modern web browser — no server or dependencies required.

## Controls

| Key | Action |
|-----|--------|
| `Arrow Up` / `W` | Move Up |
| `Arrow Down` / `S` | Move Down |
| `Arrow Left` / `A` | Move Left |
| `Arrow Right` / `D` | Move Right |
| `P` | Pause / Resume |

## Gameplay Rules

- The snake moves continuously in the current direction.
- Eating the **red food** grows the snake by one segment and increments your score.
- The game ends if the snake:
  - Hits a **wall**.
  - Collides with **itself**.
- You cannot reverse direction 180° (e.g., go directly from right to left).

## Scoring

- **Score** — increments by 1 for each food eaten in the current session.
- **Best** — highest score ever achieved, persisted in `localStorage` across sessions.

## Features

- Glowing green snake with eyes that follow movement direction.
- Glowing red food.
- Grid background for visual guidance.
- Pause/resume support.
- Best score saved locally via `localStorage`.
- Clean dark-themed UI.

## Technical Details

| Detail | Value |
|--------|-------|
| Language | Vanilla JavaScript (ES6+) |
| Rendering | HTML5 Canvas API |
| Grid size | 21 × 21 cells |
| Canvas size | 420 × 420 px |
| Game tick speed | 120 ms |
| Dependencies | None |

## Game States

```
Start Screen → Running → Paused → Running → Game Over → Running (restart)
```
