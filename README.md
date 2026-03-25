# AI Chess Practice

A browser-based chess game where you can play against an AI or watch two AI players compete.

## Features

- Play as white or black against an AI opponent
- Enable autoplay for both sides to watch AI vs AI
- Adjustable game speed (1, 2, 4, or 20 actions per second)
- Toggle board perspective between white and black POV
- Full chess rules including castling, en passant, and pawn promotion

## Usage

Open `index.html` in a browser — no build step or server required.

### Controls

- **Auto** — toggle autoplay for white and/or black
- **APS** — set actions per second (speed)
- **POV** — switch board perspective

## Project Structure

```
index.html   # App entry point and SVG piece definitions
script.js    # Game logic (Board, Piece, Constraints, Game classes)
style.css    # Board and piece styling
```
