---
layout: page
title: "Foundations of Intelligent Learning Agents"
permalink: /projects/RL/
---


  [_CS 747: Foundations of Intelligent Learning Agents_](https://www.cse.iitb.ac.in/~shivaram/teaching/cs747-a2023/index.html), [_Prof. Shivaram Kalyanakrishnan_](https://www.cse.iitb.ac.in/~shivaram/) 

## 1. Faulty Multi-Arm Bandits 
<p align="center">
    <img width="500"  src="/assets/img/opt_alg.png">
</p>

Worked on a bandit instance where pulls are no longer guaranteed to be successful and have a probability of giving faulty outputs sampled uniformly from $0$ and $1$. Derived and implemented an asymptotically optimal algorithm to minimize expected cumulative regret. The algorithm employs $Beta$ distribution sampling, similar to Thompson Sampling, while also updating its belief over the arm means based on the probability of a faulty pull.
## 2. Design Of Equalization Filter 
<p align="center">
    <img width="450"  src="/assets/img/Multi-path.png">
</p>
Implemented equalization filter design to negate the effect of ISI (Inter Symbol Interference) on the digitally transmitted message suffering from multipath reflection. Formulated a relation between the z-transform of the received signal and the transmitted signal to efficiently manage delays, and used this relation to design a suitable inverse-filter for equalization.

## 3. End-to-End Digital Communication
<p align="center">
    <img width="450"  src="/assets/img/costas.png">
</p>
Evaluated the performance of Costas Loop and Viterbi-Viterbi algorithms in discrete-time for phase and frequency offset removal in incoming signal 8-PSK using GNU Radio. Performed end-to-end transmission as well as reception of text files as a message using differential coding to handle unintentional inversion of bits in the binary waveform.
