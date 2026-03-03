# Tic Tac Toe

A clean, single-file web implementation of Tic Tac Toe with an unbeatable AI opponent.

## Features

- **Two game modes** — play against a friend or challenge the AI
- **Unbeatable AI** — uses the Minimax algorithm with alpha-beta pruning
- **Scoreboard** — tracks wins, losses, and draws across games
- **Win highlight** — the winning three cells are animated on game end
- **No dependencies** — pure HTML, CSS, and JavaScript in one file

## How to Play

Just open `tictactoe.html` in any browser — no server or install required.

- **X always goes first**
- Click a cell to place your mark
- In **vs AI** mode, you play as X and the AI plays as O
- Hit **New Game** to reset the board (scores carry over)
- Switch modes to reset scores

## AI — How It Works

The AI uses **Minimax with Alpha-Beta Pruning**:

- **Minimax** recursively simulates every possible future game state, scoring each outcome (+10 AI wins, -10 human wins, 0 draw)
- The AI picks the move that leads to the best guaranteed outcome
- **Alpha-Beta Pruning** cuts off branches that can't affect the result, making the search significantly faster

The AI plays perfectly — the best result you can achieve against it is a draw.

## Project Structure

```
tictactoe.html   — entire game: HTML structure, CSS styles, and JS logic
README.md        — this file
```

## License

MIT
