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
    <img width="450" src="/assets/img/LSTM.png">
  <br>
    <em>Performance of Trading system on test data</em>
</p>

I set up an LSTM-based stock trading system for high-frequency trading and modified it to use multiple stock prices and day of the week as inputs to predict a single stock using this [Dataset](https://www.kaggle.com/datasets/rohanrkalbag/ee782)

# Generative AI

<p align="center">
    <img width="450"  src="/assets/img/GANS.gif">
</p>

I implemented a Siamese Network using a metric learning scheme (Cosine Similarity; paired with Crossentropy) on labeled faces in the [wild (LFW) dataset](http://vis-www.cs.umass.edu/lfw/). Following this, I proceeded to train a generative model for creating facial images, initially employing a Generative Adversarial Network (GAN). 


Subsequently, I further advanced this model to function as a conditional GAN (CGAN), wherein the condition for image generation relies on a real face image of a specific individual. To achieve this, I incorporated a Siamese Discriminator, which was initially implemented in the primary task. This enhanced CGAN successfully generates additional images portraying the same individual based on these specified conditions.
