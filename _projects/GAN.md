---
layout: page
title: "Generative AI & Stock Trading System"
permalink: /projects/AdvancedML/
---


  [_EE 782: Advanced Topics in Machine Learning_](https://www.ee.iitb.ac.in/web/course_lists/ee-782-advanced-machine-learning/), [_Prof. Amit Sethi_](https://www.ee.iitb.ac.in/~asethi/)  

<div style="display: flex;">
   <a href="https://github.com/Vansh28Kapoor/Advanced-Machine-Learning/tree/main/Stock%20Trading%20System" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">LSTM-Based Stock Trading System</div>
    </a>
    <a href="https://github.com/Vansh28Kapoor/Advanced-Machine-Learning/tree/main/Generative%20AI" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">Generative AI</div>
    </a>
</div>

<br>

# Stock Trading System
<p align="center">
    <img width="450" src="/img/LSTM.png">
</p>

Set up an LSTM-based stock trading system for high-frequency trading and modified it  modify the model to use multiple stock prices and day of the week as inputs to predict a single stock using this [Dataset](https://www.kaggle.com/datasets/rohanrkalbag/ee782)

# Generative AI

<p align="center">
    <img width="480"  src="/img/GAN.png">
</p>

Implemented a Siamese Network using a metric learning scheme (Cosine Similarity; paired with Crossentropy) on labeled faces in the [wild (LFW) dataset](http://vis-www.cs.umass.edu/lfw/). Trained a generative model for generating face images, using a GAN and enhanced the model to a conditional GAN, where the condition itself is a real face image of a particular individual. The CGAN generates another image of the same person using a Siamese Discriminator implemented in the first task.
