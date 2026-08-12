# Chess-game

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Pygame](https://img.shields.io/badge/Pygame-2.0%2B-green?style=flat-square)
![python-chess](https://img.shields.io/badge/python--chess-library-yellow?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)

## Description

This project is a fully functional, interactive graphical chess game built with Python 3 and Pygame. It provides a complete chess experience with strict enforcement of standard chess rules, real-time match statistics, and an integrated graphical user interface.

Players can enjoy a local 1v1 multiplayer mode or challenge a computer-based AI opponent. The built-in AI utilizes the Minimax algorithm with Alpha-Beta pruning to evaluate board states and make intelligent decisions, offering a challenging match for players.

## Features

* **Dual Game Modes:** Choose between playing against a friend locally (Multiplayer) or testing your skills against the machine (AI).
* **Smart AI Opponent:** Features an AI that uses Alpha-Beta pruning and a static evaluation function based on standard piece values (Pawn=1, Knight/Bishop=3, Rook=5, Queen=9).
* **Interactive GUI:** A clean graphical interface built with Pygame that supports mouse clicks for moving pieces, highlights selected squares, and provides a main menu to choose sides (Play as White or Black).
* **Live Match Dashboard:** A dynamic side panel that tracks both players' elapsed time and visually displays captured pieces.
* **Strict Rule Enforcement:** Powered by the `python-chess` library, it automatically handles legal move validation, pawn promotion, checkmates, and advanced draw conditions (stalemate, insufficient material, 75-move rule, fivefold repetition).

## Tech Stack

* **Language:** Python 3
* **Graphics & GUI:** Pygame
* **Chess Logic Engine:** `python-chess` (imported as `chess`)

## Getting Started

### Prerequisites

Ensure you have Python 3.8 or higher installed. It is recommended to use a virtual environment.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/cl4sic/Chess-game.git](https://github.com/cl4sic/Chess-game.git)
   cd Chess-game
