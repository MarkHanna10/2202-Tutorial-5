# Tic-Tac-Toe Board (DOM and Events)

A two-player tic-tac-toe board built with plain JavaScript and DOM manipulation. A tutorial exercise for SE 2202 at Western University.

## What the code does

- Generates the 3×3 board at load time by injecting a button into each table cell
- Attaches a `click` listener to every button with `addEventListener`
- Marks a cell with `X` or `O`, disables the cell, and alternates turns
- Shows whose turn comes next, and shows "Game Over" once every cell is taken

## Run

Open `index.html` in a browser. Refresh the page to start a new game.

## Files

| File | Role |
| --- | --- |
| `index.html` | Board table and status labels |
| `scripts.js` | Board setup, click handling and game-over check |

---

Built by [Mark Hanna](https://github.com/MarkHanna10).
