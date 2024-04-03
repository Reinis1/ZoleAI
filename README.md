# ZoleAI
## Overview
The Zole AI Model is a neural network-based artificial intelligence designed to play the Latvian traditional card game's Zole game mode "Table". It is trained using reinforcement learning techniques for 1 million games to make strategic decisions during gameplay. This model serves as an autonomous player capable of competing against human players or other AI opponents. 
## Features
**Gameplay Simulation:** The AI model simulates Zole gameplay by predicting the best moves based on the current game state and historical data. The model has all the same information as a human player would and no more.
**Customizable Difficulty:** The AI's difficulty level can be adjusted to provide varying levels of challenge to players.
**Online Demo:** An online sandbox demo allows users to interact with the AI model through a user-friendly interface, experiencing its gameplay capabilities firsthand.

## How It Works
The Zole AI Model utilizes a deep neural network architecture to learn optimal gameplay strategies. Here's an overview of its functioning:
1. **Input Processing:** The current game state, including the player's hand, cards on the table, and game rules, is processed as input to the neural network.
2. **Neural Network Inference:** The processed input is fed into the neural network, which outputs a probability distribution over possible actions the AI can take.
3. **Action Selection:** Based on the output probability distribution, the AI selects the action with the highest predicted reward or utility.
4. **Game Execution:** The selected action is executed in the game simulation environment, and the gameplay continues.
5. **Feedback and Learning:** After each game iteration, the AI receives feedback on the outcome of its actions. This feedback is used to update the neural network parameters through reinforcement learning techniques, improving the AI's decision-making abilities over time.
## Online Demo
The Zole AI Model comes with an online demo where users can play against the AI in a simulated Zole game environment. The demo provides the following functionalities:
- See all player's and/or table cards.
- 
