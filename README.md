# AI for Self Driving Car

## Overview

This project involves creating an AI for a self-driving car using a Deep Q-Network (DQN) and the Kivy framework for graphical user interface. The project includes the implementation of the neural network, experience replay, and DQN algorithm, as well as the simulation environment for testing and training the self-driving car.

## Project Structure
.
├── .idea/                # Contains IDE-specific files.
├── __pycache__/          # Contains Python bytecode files.
├── .DS_Store             # MacOS file metadata.
├── .gitignore            # Specifies files and directories to be ignored by git.
├── README.md             # This document.
├── ai.py                 # Contains the AI implementation, including the neural network, experience replay, and DQN.
├── car.kv                # Kivy language file for defining the user interface.
├── last_brain.pth        # Saved state of the trained model.
├── map.py                # Main script for running the self-driving car simulation.
├── map_commented.py      # Commented version of `map.py` for better understanding of the code.
├── requirements.txt      # Lists the required Python packages to run the project.
├── run.sh                # Shell script to start the project.
└── specifications/       # Project specifications and design documents.

## Dependencies

The project requires the following Python libraries:

- numpy
- torch
- kivy
- matplotlib

You can install the required libraries using:

```sh
pip install -r requirements.txt
