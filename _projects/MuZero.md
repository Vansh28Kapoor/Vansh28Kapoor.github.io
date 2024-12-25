---
layout: page
title: MuZero VS Model-Free RL
permalink: /projects/MuZero/
description:
display_categories: [work, fun]
nav: false
horizontal: false
---
  [_10 715: Deep Reinforcement Learning and Control_](https://cmudeeprl.github.io/703website_f24/), [_Prof. Katerina Fragkiadaki_](https://www.cs.cmu.edu/~katef/) 

<div style="display: flex;">
    <a href="https://github.com/Vansh28Kapoor/MuZero" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">GitHub</div>
    </a>
</div>

<be>


Evaluated the performance of model-free RL algorithms (Actor-Critic, DQN, REINFORCE) against the model-based MuZero algorithm on the CartPole-v1 environment in Gymnasium.


## MuZero
<p align="center">	
    <img width="500"  src="/assets/img/MuZero.png">	
</p>	


Implemented a non-parallelized version of the MuZero algorithm to solve the OpenAI Gym CartPole-v1 environment. Developed key components of the Monte Carlo Tree Search (MCTS), including child selection, node expansion, backpropagation, and action sampling. Designed neural network architectures for state representation, dynamics prediction, value estimation, policy prediction, and reward prediction. Created a training loop for the MuZero agent with loss functions for value, policy, and reward predictions, achieving convergence within 30 training epochs. Conducted hyperparameter tuning experiments to optimize MCTS simulations and analyzed their impact on performance, while visualizing training metrics such as test rewards and loss components.	

<p align="center">	
    <img width="500"  src="/assets/img/MuZeroloss.png">	
</p>	

## Model-Free Algorithms: A2C & DQN

<p align="center">	
    <img width="500"  src="/assets/img/A2C.gif">	
</p>


<p align="center">	
    <img width="500"  src="/assets/img/DQN.png">	
</p>	
