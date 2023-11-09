---
layout: page
title: "Foundations of Intelligent Learning Agents"
permalink: /projects/RL/
---


  [_CS 747: Foundations of Intelligent Learning Agents_](https://www.cse.iitb.ac.in/~shivaram/teaching/cs747-a2023/index.html), [_Prof. Shivaram Kalyanakrishnan_](https://www.cse.iitb.ac.in/~shivaram/) 

  <div style="display: flex;">
    <a href="/assets/pdf/Billiards.pdf" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">Slides</div>
    </a>
    <a href="https://github.com/Vansh28Kapoor/Reinforcement-Learning" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">GitHub</div>
    </a>
</div>

<br>

## 1. Reinforcement Learning for Playing Billiards
<p align="center">
    <img width="450"  src="/assets/img/pool.gif">
</p>

The task of this project is to code an agent that provides us with optimal force and angle at which the cue ball has to be struck, such that it pots all the solid balls within the maximum tries limit. In order to mimic real scenarios where high force to cue ball cultivates to less control, guassian noise proportional to the force is added to the angle provided by the agent to the cue ball.


I coded an agent that employed decision-time planning using Monte-Carlo Tree Search (MCTS) to identify the most suitable ball to pot and to determine the force that should be applied to the ball along with optimal angle. This provides robustness to the Gaussian Noise added to the input angle to the cue ball. I discounted the reward (balls potted) obtained in the future time-step by a factor of 0.25. Thus, by utilizing and discounting the future time-step reward, I established an effective policy for the cue ball.


My intermediate experiments that made be realize the importance of tree search, specifically the advantage of tree search for a depth of two when only a single target ball is remaining. Using a depth of two proved to be quite advantageous since the cue ball took an action that had very high probability of potting the single target ball in at max two tries.

## 2. MDP Planning for Half-Field Offense in Football  
<p align="center">
    <img width="250"  src="/assets/img/football.gif">
</p>
For any input Markov Decision Process (MDP), I coded up a MDP-planner that can use Value Iteration, Linear Programming or Howard's Policy Iteration to find the optimal policy V* for the MDP. Furthermore using  MDP Planning, I devised a strategy to maximize the  goal-scoring probabilities for a two-player football team attempting to score a goal against a single opponent in a game of football. In such a formulation of the MDP, my Value function of a state is the expected number of goals starting from the initial state.
<p align="center">
    <img width="450"  src="/assets/img/policy.jpg">
</p>
