# TetrisAI
This project is an implementation of the classic game of Tetris, but the twist is it is played by an AI-algorithm. This AI has been trained to make strategic decisions for placing and rotating falling tetrominos in order to clear lines and achieve the highest score possible.
## Features:
- Classic Tetris gameplay experiencee
- AI-driven decision making for tetromino placement.
- Real-time visualization of the AI gameplay
- Score tracking for the current game session

## Installation
-Make sure you have Python 3.x installed on your system.
-Clone the Repository.
-Navigate to the directory.
-run the game using the command: 
  python main.py

## Algorithm Used:
The AI algorithm used in this project is MCTS (Monte Carlo Tree Search) algorithm. MCTS simulates a sequence of potential moves and outcomes, gradually building a tree of possible game states. In the context of Tetris, MCTS evaluates different placements and rotations of tetrominos, estimating their potential to clear lines and maximize the player's score. By iteratively exploring and expanding the game tree, MCTS helps the AI ake informed decisions about the most promising moves. This method enables the Tetris AI to exhibit strategic thinking and adapt to various in-game scenarios, contributing to more intelligent and efficient gameplay.
