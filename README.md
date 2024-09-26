# Pygame Chess Engine

## Table of Contents
1. [Project Information](#project-information)
2. [Technologies](#technologies)
3. [Features](#features)
4. [Further Development Ideas](#further-development-ideas)
5. [Instructions](#instructions)

## Project Information
This Chess Engine was made in Pygame. It uses simple algorithms such as alpha-beta pruning, where it evaluates moves by simulating future positions to a fixed depth.

I played chess from a very young age and always wanted to make my own chess engine from scratch! This engine is very simple and easy, hence it is not as advanced as I would like it to be. I will continue working on it, or on other chess projects to improve the AI (and UI of course)!

## Technologies
- **Python 3.8+**
- **Pygame 2.0.x**

## Features
- Play against a computer (basic AI) or another player locally.
- Move generation and validation for all standard chess rules.
- Detects check, checkmate, and stalemate conditions.
- Undo and restart functionality for easy game control.
- Move Notation and simple UI.

## Further Development Ideas
- Clean up Code.
- Use numpy arrays instead of 2D lists.
- Menu to select 2 players or play against the AI.
- Add other piece options when promoting pawns.
- For better algorithms: Look at checks, captures and threats first. Prioritize castling/king safety.
- To improve alpha-beta pruning, start with moves that previously score higher.
- Incorporate 

## Instructions
1. Clone this repo.
2. Install requirements.txt
2. Select if you want to play versus the AI, or another player locally. Look at ChessMain.py lines 43 and 44 and set the flags accordingly.
3. Run ChessMain.py.
4. Play!

- Press z to undo a move.
- Press r to reset the game.

