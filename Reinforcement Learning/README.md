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
**Other environments:** 'adventure', 'air_raid', 'alien', 'amidar', 'assault', 'asterix', 'asteroids', 'atlantis', 'bank_heist', 'battle_zone', 'beam_rider', 'berzerk', 'bowling', 'boxing', 'breakout', 'carnival', 'centipede', 'chopper_command', 'crazy_climber', 'defender', 'demon_attack', 'double_dunk', 'elevator_action', 'enduro', 'fishing_derby', 'freeway', 'frostbite', 'gopher', 'gravitar', 'hero', 'ice_hockey', 'jamesbond', 'journey_escape', 'kaboom', 'kangaroo', 'krull', 'kung_fu_master', 'montezuma_revenge', 'ms_pacman', 'name_this_game', 'phoenix', 'pitfall', 'pong', 'pooyan', 'private_eye', 'qbert', 'riverraid', 'road_runner', 'robotank', 'seaquest', 'skiing', 'solaris', 'space_invaders', 'star_gunner', 'tennis', 'time_pilot', 'tutankham', 'up_n_down', 'venture', 'video_pinball', 'wizard_of_wor', 'yars_revenge', 'zaxxon'
