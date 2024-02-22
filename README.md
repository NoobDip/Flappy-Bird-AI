# Flappy Bird NEAT AI

## Overview

This Python script (`flappy_bird.py`) implements the classic Flappy Bird game using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm for training an AI agent to play the game. The game is built using the Pygame library, and the NEAT algorithm is employed to evolve a neural network that controls the bird's actions.

## Requirements

- Python 3.7 or later
- Pygame
- NEAT-Python library

## Usage

1. **Install Dependencies:**
   - Install the required dependencies by running the following command:
     ```bash
     pip install pygame neat-python
     ```

2. **Run the Script:**
   - Execute the script using the following command:
     ```bash
     python flappy_bird.py
     ```
   - The script will initiate the NEAT algorithm to evolve a neural network that controls the bird in the Flappy Bird game.

3. **Game Controls:**
   - The game starts automatically, and the AI-controlled bird will attempt to navigate through pipes.
   - Observe the AI's performance and watch as it improves over multiple generations.

4. **Training Progress:**
   - The script will display information about the current generation, score, and the number of birds alive.
   - The NEAT algorithm will evolve the neural network over several generations to improve the bird's performance.

5. **Exiting the Game:**
   - To exit the game, close the game window, and the script will terminate.

## Script Components

- **Flappy Bird Game:** The game environment where the AI-controlled bird attempts to navigate through pipes.

- **NEAT Algorithm:** The NEAT algorithm is used to evolve the neural network that controls the bird's actions. The neural network takes input features such as bird height and distances to pipes to make decisions.

- **Pygame Visualization:** Pygame is utilized to create a simple graphical interface for visualizing the Flappy Bird game and the AI's performance.

## Configuration

- **NEAT Configuration:** The NEAT algorithm's configuration is specified in the `config-feedforward.txt` file. This file defines parameters such as population size, mutation rates, and neural network structure.

## Customization

- **Game Parameters:** Adjust the game parameters, such as pipe gap size, bird jump height, and screen dimensions, within the script.

- **NEAT Configuration:** Modify the `config-feedforward.txt` file to experiment with different NEAT algorithm parameters.

## Acknowledgments

- This script is inspired by the NEAT-Python library examples and the Flappy Bird game.


Feel free to use and modify the script for educational and experimental purposes. If you find it helpful, consider giving credit to the NEAT-Python library and the original authors of the Flappy Bird game.
