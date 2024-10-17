# NIM GAME with AI

This project is a Python implementation of the Nim game with an AI that learns optimal strategies using Q-learning. The AI can be trained to play efficiently, and humans can play against the AI to test its performance.

## Features
- **Game Logic**: Implements the traditional rules of Nim with customizable initial piles.
- **AI Learning**: Uses Q-learning to train the AI by playing several games against itself.
- **Epsilon-Greedy Strategy**: AI balances exploration and exploitation to discover optimal moves.
- **Human vs. AI Mode**: Allows a human player to challenge the AI.
  ![image](https://github.com/user-attachments/assets/1323586b-aaec-403f-9ab8-d4ceb105647e)

## Q-Learning Algorithm
The AI learns using Q-learning, a popular reinforcement learning technique where it updates a Q-value table based on the following:  

- **Old Q-value**: The current estimation of the value of taking a particular action in a given state.  
- **Reward**: A feedback score based on the result of the action (positive for winning moves, negative for losing).  
- **Future Rewards**: The best possible outcome from the new state after taking the action.  
# License
This project is licensed under the MIT License - see the LICENSE file for details. 
