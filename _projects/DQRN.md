---
layout: page
title: "Deep Recurrent Q-Learning for Partially Observable MDPs"
permalink: /projects/DQRN/
---


  [_CS 782: Advanced Topics in Machine Learning_](https://www.ee.iitb.ac.in/web/course_lists/ee-782-advanced-machine-learning/), [_Prof. Amit Sethi_](https://www.ee.iitb.ac.in/~asethi/) 

  <div style="display: flex;">
        <a href="/assets/pdf/EE782_Project.pdf" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">Report</div>
    </a>
    <a href="https://github.com/Vansh28Kapoor/EE782-project" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">GitHub</div>
    </a>
</div>

<br>

<p align="center">
    <img width="450"  src="/assets/img/DQRN.gif">
</p>

# Deep Recurrent Q Learning for POMDP

The project presents a unique implementation of an RL-LSTM-Q Network for faster convergence towards optimality while playing Atari 2600 games such as Assault v-5 and Bowling. The innovations implemented include the utilization of domain knowledge for reward function implementation, a rolling window for memory optimization, Cosine Annealing for adapting to escalating difficulty levels, and Transfer Learning using ResNet-18 for image feature extraction, among others.

<p align="center">
    <img width="450" src="/assets/img/DQN.png">
    <br>
    <em>Double Deep Q-Network</em>
</p>

## The Architecture Breakdown

To approach this complex problem, the project developed a series of classes designed to establish a robust infrastructure for learning and memory management.

### 1. `LSTM` and `Net`
A custom Long Short-Term Memory (LSTM) module, known as `LSTM`, was crafted for sequential processing. This was combined with the `Net` class, encompassing convolutional layers and pooling operations to efficiently capture spatiotemporal dependencies and process image sequences.

### 2. `RL_LSTM_Q_Network`
At the core of the architecture, the `RL_LSTM_Q_Network` class amalgamated convolutional layers with LSTM to craft an RL agent precisely tuned to navigate POMDP scenarios.

### 3. `Agent`, `DeepMemory`, and `EpisodicMemory`
The `Agent` class took center stage, responsible for managing memories, predicting actions, and orchestrating the training of the model. It utilized the `DeepMemory` and `EpisodicMemory` classes, providing a structured and efficient way to manage the vast data accumulated during the learning process.

### 4. Utility Functions
In addition to the core learning components, the project introduced utility functions for visualizing frames, rewards, and creating GIFs from frames. These functions provided critical insights into the model's learning process.

## Rolling Window Optimization for Memory

<p align="center">
    <img width="450" src="/assets/img/avg-plot.png">
    <br>
    <em>Performance of RL Agent with iterations for Assault-v5</em>
</p>

## Domain Knowledge for Reward Function Implementation

Utilizing domain knowledge rooted in general human gameplay, strategies are applied to allocate rewards effectively to the agent. Vanilla Q-Learning loss, assessment of shooting frequency, and consideration of gameplay duration collectively contribute to enhancing the agent's survivability in the game. This method prevents overheating from continuous firing and prompts selective 'shooting' actions as necessary. Training based on these human-inspired strategies aims to elevate the agent's performance beyond human-level gameplay.

<p align="center">
    <img width="450" src="/assets/img/plot-assualt.png">
    <br>
    <em>Performance Evaluation of Proposed Approach</em>
</p>

## Concluding Remarks

The integration of recurrent and deep Q-learning strategies within POMDP scenarios showcases the merging of diverse neural network paradigms. This project signifies a substantial stride towards conquering the intricate challenges embedded in the realm of POMDP, potentially leading to breakthroughs in handling complex real-world decision-making problems.
