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

Worked on a bandit instance where pulls are no longer guaranteed to be successful and have a probability of giving faulty outputs sampled uniformly from '$0$' and '$1$'. Derived and implemented an asymptotically optimal algorithm to minimize expected cumulative regret. The algorithm employs '$Beta$' distribution sampling, similar to Thompson Sampling, while also updating its belief over the arm means based on the probability of a faulty pull.
