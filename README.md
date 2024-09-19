

https://github.com/user-attachments/assets/589f1af1-37e7-49ea-93f4-489b18767604

# Connect 4 Game Repository

Welcome to the Connect 4 Game repository! This project contains two versions of the classic Connect 4 game: one with an AI opponent and one for multiplayer play. The game is implemented in Python using the Pygame library and utilizes NumPy for game logic.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
  - [AI Version](#ai-version)
  - [Multiplayer Version](#multiplayer-version)
- [How to Play](#how-to-play)
  - [AI Version](#ai-version-1)
  - [Multiplayer Version](#multiplayer-version-1)
- [AI Version Details](#ai-version-details)
- [Multiplayer Version Details](#multiplayer-version-details)
- [License](#license)

## Overview

Connect 4 is a two-player board game where players take turns dropping colored discs into a vertical grid. The goal is to connect four of one's own discs in a row, either horizontally, vertically, or diagonally. This repository includes:

1. **AI Version** (`main.py`): Play against an AI opponent that uses a minimax algorithm with alpha-beta pruning.
2. **Multiplayer Version** (`game.py`): Play against a friend locally with two-player mode.

## Requirements

To run the games, you need to have Python installed along with the following packages:

- `pygame`
- `numpy`

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Hamadabcn/connect4ai.git
   cd connect4ai
2. **Install the required packages**: You can install the required packages using pip. It is recommended to use a virtual environment to manage dependencies.
    ```bash
    pip install pygame numpy

## Usage
## AI Version

3. **To play against the AI, run the main.py script**:
   ```bash
   python main.py
4. **Multiplayer Version To play in multiplayer mode, run the game.py script**:
   ```bash
   python game.py

## How to Play

## AI Version
1. **The game starts with the AI making its move**.
2. **Click on a column to drop your disc**.
3. **The game will alternate between your moves and the AI's moves**.
4. **The game ends when a player connects four discs in a row, and a message will be displayed**.
## Multiplayer Version
1. **Player 1 (Red) and Player 2 (Yellow) take turns to click on a column to drop their discs**.
2. **The game will alternate between Player 1 and Player 2**.
3. **The game ends when one player connects four discs in a row, and a winning message will be displayed**.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

    
