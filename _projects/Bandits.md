---
layout: page
title: Online Learning
permalink: /projects/Online-Learning
description:
display_categories: [work, fun]
nav: false
horizontal: false
---
  [_CS 747: Foundations of Intelligent Learning Agents_](https://www.cse.iitb.ac.in/~shivaram/teaching/cs747-a2023/index.html), [_Prof. Shivaram Kalyanakrishnan_](https://www.cse.iitb.ac.in/~shivaram/) 

  <div style="display: flex;">
    <a href="/assets/pdf/Billiards.pdf" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">Report</div>
    </a>
    <a href="https://github.com/Vansh28Kapoor/Online-Learning" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">GitHub</div>
    </a>
</div>

<br>

## 1. Faulty Multi-Arm Bandits 	
<p align="center">	
    <img width="500"  src="/assets/img/opt_alg.png">	
</p>	

I worked on a bandit instance where pulls are no longer guaranteed to be successful and have a probability of giving faulty outputs sampled from a uniform distribution _Unif(0,1)_. I derived and implemented an asymptotically optimal algorithm to minimize the expected cumulative regret. This algorithm employs _Beta_ distribution sampling, similar to Thompson sampling, while also updating its belief over the arm means based on the probability of a faulty pull.

## 2. Batched Multi-armed Bandits Problem
  For this task, we had to implement an efficient algorithm for batched sampling, i.e., at every time-step, we were allowed to pull only a fixed number of arms. I devised an asymptotically optimal algorithm that generalizes for arbitrary batch sizes. I approached the problem by implementing a batched sampling variant of Thompson Sampling and KL-UCB that stochastically sampled multiple times from the belief distribution it had of the Bernoulli arms.
