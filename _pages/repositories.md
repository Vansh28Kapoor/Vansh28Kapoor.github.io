---
layout: page
permalink: /Research/
title: Research
description: 
nav: true
nav_order: 1
---

## 1. Partially Observable MDPs with State Sensing Cost 
_Research project with [Prof. Jayakrishnan Nair ](https://www.ee.iitb.ac.in/~jayakrishnan.nair/)_    

In many practical sequential decision-making problems, tracking the state of the environment incurs an additional  sensing/communication/computation cost. We formulated this as a classical expected discounted cost Markov Decision Process (MDP), wherein the agent incurs an additional cost for sensing its next state, but has the choice to take actions while remaining `blind' to the system state. 

Since a policy in this setting maps each state to a sequence of actions that an agent plays till sensing, each policy can map a state to a string of actions of possibly infinite length, i.e., there is no limit on the number of possible policies. While computing the optimal policy for this MDP is intractable in general, we bounded the sub-optimality gap associated with optimal policies in a restricted class, where the number of consecutive non-sensing (a.k.a., blind) actions is capped. We also designed a computationally efficient heuristic algorithm based on policy improvement, which in practice performs close to the optimal policy. We finally numerically evaluate our results via a case study based on inventory management. 

In recognition of my contributions to this research, I was awarded the *Undergraduate Research Award (URA01)* from IIT Bombay, and this work was submitted to *AAAI-25*, where I am the first author.

## 2. Early Rumor Detection 
_In collaboration with Google AI research, along with [Dr. Manish Jain](https://www.linkedin.com/in/manish-jain-kj2020/) and [Prof. Nikhil Karamchandani](https://sites.google.com/site/nikhilkaram/)_  


I got an opportunity to collaborate with Google AI Research to design effective models for for analyzing the spread of various contagion processes on social networks. Our project focuses on countering coordinated bot attacks aimed at spreading rumors across different social media platforms like YouTube.  We are employing Online Learning techniques to assess the credibility of individual users within the social network and subsequently applying deep learning-based cascade models to enable more precise  management of information dissemination.

<p align="center">
    <img width="350" src="/assets/img/info.png">
</p>
