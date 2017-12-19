## Overview

|Environment:     |All OpenAI Gym's Atari Games
|:---------|:---
|Purpose   |Use CNTK to define Deep Q Neural Network (Mnih & al, 2013), a value-based Deep Reinforcement Learning method inspired by Q-Learning method. The program will learn how to play any Atari game.
|Network   |DeepQNeuralNetwork (DQN).
|Actions  |Sampled from space.
|Comments |Using Dynamic Atari Learning Environment (ALE)

## Running the example

python DeepQNeuralNetwork.py -e [epochs] -p [environment]

Some options are available: 

- -e : Number of epochs to run (1 epoch = 250.000 actions taken)
- -p : Turn on tensorboard plotting, to visualize training
- Environment name, provided as trailing parameter to easily change the ALE environment
 
 Example:
 
 `
 python DeepQNeuralNetwork.py -e 200 -p SpaceInvaders-v0
 `
