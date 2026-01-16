---
layout: page
permalink: /Research/
title: Research
description: 
nav: true
nav_order: 1
---

### MDPs with State Sensing Costs

**<u>Vansh Kapoor</u>**, Jayakrishnan Nair  
[Paper ↗](https://arxiv.org/abs/2505.03280) · [GitHub](https://github.com/Vansh28Kapoor/POMDPs-With-Sensing-Cost)

*Under review at AISTATS’26*

I worked on the problem of sequential decision-making with costly state sensing, where an agent must determine not only which action to take but also when acquiring state information is worth the sensing cost. We reformulated this original Partially Observable MDP (POMDP) as an equivalent MDP by expanding the state space, enabling the use of classical dynamic programming tools such as Bellman equations and the Policy Improvement Theorem. Building on this formulation, I designed SPI (Selective Policy Improvement)—a novel algorithm that achieves near-optimal sensing strategies and consistently outperforms state-of-the-art POMDP solvers, while scaling gracefully to continuous state spaces via function approximation. I also derived analytic lower bounds on the optimal value function, which allowed explicit computation of suboptimality gaps for arbitrary policies. This work was recognized with the *Undergraduate Research Award* at IIT Bombay.

---

### TRIM: Hybrid Inference via Targeted Stepwise Routing in Multi-Step Reasoning Tasks

**<u>Vansh Kapoor</u>**, Aman Gupta, Hao Chen, Anurag Beniwal, Jing Huang, Aviral Kumar  
[Paper ↗](https://arxiv.org/abs/2601.10245)  

*Under review at ICLR’26*

As an *Applied Science AI Intern at Amazon*, I led a research project on dynamic LLM routing for multi-step reasoning tasks, aiming to intelligently allocate computation across a cheap, weaker model and a strong, expensive model under arbitrary token–cost constraints. I developed both RL–based and POMDP-based routing policies that decide, at each reasoning step, which model should generate the next sequence of tokens. Our system achieved up to 5× higher cost efficiency than SOTA routing baselines on challenging benchmarks such as AIME and MATH-500, while matching the accuracy of the expensive model using 75% fewer expensive-model tokens. This work introduces a principled alternative to one-shot query routing by treating routing as a sequential decision problem


<p align="center">
    <img width="800" src="/assets/img/Stepwise_Setup.png">
</p>

---


### Early Rumor Detection

_In collaboration with Google DeepMind, along with [Prof. Nikhil Karamchandani](https://sites.google.com/site/nikhilkaram/) and [Dr. Manish Jain](https://www.linkedin.com/in/manish-jain-kj2020/)_

I got an opportunity to collaborate with Google Research for my Bachelor’s Thesis project with Prof. Nikhil  Karamchandani to develop algorithms to counter coordinated bot attacks spreading rumors on social platforms like YouTube. Modeling these platforms as large-scale social graphs, we designed multi-step lookahead algorithms that leverage crowd-sourced signals for robust rumor detection.  To ensure scalability, we developed efficient approximations of our algorithms that enabled them to operate effectively on large, complex networks. Our method consistently outperformed state-of-the-art greedy algorithms while maintaining computational efficiency. We evaluated our approach across diverse graph structures, including those with adversarial and low-reliability users that mimic real-world information propagation, and demonstrated strong robustness to both malicious and uninformed agents. Furthermore, we established theoretical performance guarantees, including regret bounds for this class of multi-step lookahead algorithms.

<p align="center">
    <img width="250" src="/assets/img/info.png">
</p>
