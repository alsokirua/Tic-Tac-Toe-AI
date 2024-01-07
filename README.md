# Tic-Tac-Toe AI with Alpha-Beta Pruning

## Overview
This project implements an AI to play Tic-Tac-Toe optimally. It uses the Minimax algorithm with optional Alpha-Beta pruning to enhance efficiency. The AI is designed to make the best move from any given game state, ensuring it either wins or draws.

## Features
- **Optimal Tic-Tac-Toe Gameplay**: The AI always plays the best possible move.
- **Minimax Algorithm**: Implements the Minimax algorithm to evaluate the best move.
- **Alpha-Beta Pruning (Optional)**: Includes an option to use Alpha-Beta pruning to reduce the number of nodes evaluated, thus improving performance.

## Requirements
- Python 3.x
- Any modern IDE (optional)

## Installation
Clone the repository:
```
git clone https://github.com/alsokirua/tic-tac-toe-ai.git
cd tic-tac-toe-ai
```

## Usage
Run the program:
```
python tic_tac_toe_ai.py
```

To enable Alpha-Beta pruning, modify the relevant function call in the code or set a flag in the command line, as per the implementation details.

## Implementation Details
The AI is implemented in Python. The `tic_tac_toe_ai.py` file contains the main logic for the AI. The Minimax algorithm is used to evaluate all possible moves and choose the best one. Alpha-Beta pruning can be enabled to improve efficiency by reducing the number of game states evaluated.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
