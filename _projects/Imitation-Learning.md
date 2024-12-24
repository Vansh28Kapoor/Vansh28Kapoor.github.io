---
layout: page
title: Imitation Learning using Denoising Diffusion Models
permalink: /projects/Imitation-Learning
description:
display_categories: [work, fun]
nav: false
horizontal: false
---
  [_CS 747: Foundations of Intelligent Learning Agents_](https://cmudeeprl.github.io/703website_f24/), [_Prof. Katerina Fragkiadaki_](https://www.cs.cmu.edu/~katef/) 

<div style="display: flex;">
    <a href="https://github.com/Vansh28Kapoor/Imitation-Learning" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">GitHub</div>
    </a>
</div>

<br>

## Diffusion Policy
<p align="center">	
    <img width="500"  src="/assets/img/Diffusion-policy.png">	
</p>	
Implemented Imitation Learning using diffusion policies for the BipedalWalker-v3 environment in Gymnasium. Designed a transformer-based policy architecture takes as input a history of states, actions, and episode timesteps and predicts future actions through denoising diffusion process. The expert trajectories to imitated were supplied by the Proximal Policy Optimization (PPO) algorithm as a substitute for human demonstrations.

## DAgger & Behavior Cloning
<p align="center">	
    <img width="500"  src="/assets/img/Dagger_Algo.png">	
</p>
<p align="center">	
    <img width="500"  src="/assets/img/DAgger.png">	
</p>	
Implemented DAgger and Behavior Cloning by training a policy through supervised regression to map observations to actions using a dataset of expert trajectories (state-action pairs). Designed a residual three-layer multilayer perceptron (MLP) as the policy network, outputting actions within the range [-1, 1]. he average, median, and max reward for each
batch collection step when collecting trajectories using the DAgger model, and plot
the results
<p align="center">	
    <img width="500"  src="/assets/img/DAgger.png">	
</p>	
<p align="center">	
    <img width="500"  src="/assets/img/BC.gif">	
</p>	

