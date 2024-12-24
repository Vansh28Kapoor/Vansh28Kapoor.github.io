---
layout: page
title: Imitation Learning using Denoising Diffusion Models
permalink: /projects/Imitation-Learning
description:
display_categories: [work, fun]
nav: false
horizontal: false
---
  [_CS 747: Foundations of Intelligent Learning Agents_](https://www.cse.iitb.ac.in/~shivaram/teaching/cs747-a2023/index.html), [_Prof. Shivaram Kalyanakrishnan_](https://www.cse.iitb.ac.in/~shivaram/) 

  <div style="display: flex;">
    <a href="/assets/pdf/Bandits.pdf" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">Report</div>
    </a>
    <a href="https://github.com/Vansh28Kapoor/Online-Learning" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">GitHub</div>
    </a>
</div>

<br>

## 
<p align="center">	
    <img width="500"  src="/assets/img/Diffusion-policy.png">	
</p>	
Implemented Imitation Learning using diffusion policies for the BipedalWalker-v3 environment in Gymnasium. Designed a transformer-based policy architecture takes as input a history of states, actions, and episode timesteps and predicts future actions through denoising diffusion process. The expert trajectories to imitated were supplied by the Proximal Policy Optimization (PPO) algorithm as a substitute for human demonstrations.

## 2. Batched Multi-armed Bandits Problem
<p align="center">	
    <img width="500"  src="/assets/img/ucb.jpg">	
</p>	
  For this task, we had to implement an efficient algorithm for batched sampling, i.e., at every time-step, we were allowed to pull only a fixed number of arms. I devised an asymptotically optimal algorithm that generalizes for arbitrary batch sizes. I approached the problem by implementing a batched sampling variant of Thompson Sampling and KL-UCB that stochastically sampled multiple times from the belief distribution it had of the Bernoulli arms.


Furthermore, I devised an efficient algorithm for multiple bandit instances where the horizon equals the number of arms. The primary aim of the task was to design an algorithm capable of performing significantly better than simply sampling each arm once.
