![LogoFinal](https://github.com/Reinis1/ZoleAI/assets/112851463/2a1e244c-9dcf-4dc6-8631-55559478702b)
# ZoleAI
## Version 1.0.0 - Published 2024 Apr 7
## Overview
The Zole AI Model is a neural network-based artificial intelligence designed to play the Latvian traditional card game's Zole game mode "Table". It is trained using reinforcement learning techniques for 1 million games to make strategic decisions during gameplay. This model serves as an autonomous player capable of competing against human players or other AI opponents. \n

## Features
- **Gameplay Simulation:** The AI model simulates Zole gameplay by predicting the best moves based on the current game state and historical data. The model has all the same information as a human player would and no more.
- **Customizable Difficulty:** The AI's difficulty level can be adjusted to provide varying levels of challenge to players.
- **Online Demo:** An [online sandbox demo](#online-demo) allows users to interact with the AI model through a user-friendly interface, experiencing its gameplay capabilities firsthand.

## How It Works
The Zole AI Model utilizes a deep neural network architecture to learn optimal gameplay strategies. Here's an overview of its functioning:
1. **Input Processing:** The current game state, including the player's hand, cards on the table, and game rules, is processed as input to the neural network.
2. **Neural Network Inference:** The processed input is fed into the neural network, which outputs a probability distribution over possible actions the AI can take.
3. **Action Selection:** Based on the output probability distribution, the AI selects the action with the highest predicted reward or utility.
4. **Game Execution:** The selected action is executed in the game simulation environment, and the gameplay continues.
5. **Feedback and Learning:** After each game iteration, the AI receives feedback on the outcome of its actions. This feedback is used to update the neural network parameters through reinforcement learning techniques, improving the AI's decision-making abilities over time.
## Online Demo 
The Zole AI Model comes with an [online demo](https://unsealable.itch.io/zole) where users can play against the AI in a simulated Zole game environment. 

![image](https://github.com/Reinis1/ZoleAI/assets/112851463/560c27e1-562f-4df6-a920-55d5e0ab59a2)

The demo provides the following functionalities:
- Select any of the 5 trained models. Each with a different ammount of steps trained.
- See all player's and/or table cards.
- Play an illegal card (User only).
- See an evaluation score the selected AI model assigns to each card. 
- Request the AI to evaluate user's gamplay by assigning PSAE score to each action.
- Controll how quickly an AI plays a card by adjusting the simulation speed.
