---
layout: page
permalink: /projects/Multi-face/
---
<h1><b>Real-Time Rapid Visual Multi-Face Detector</b></h1>  

  [_EE 769: Introduction to Machine Learning_](https://www.ee.iitb.ac.in/web/course_lists/ee-768-introduction-to-machine-learning/), [_Prof. Amit Sethi_](https://www.ee.iitb.ac.in/~asethi/)  
  
[Report](assets/pdf/Project_Report) | [Github](https://github.com/Vansh28Kapoor/RAPID-VISUAL-MULTI-FACE-DETECTION) 



<p align="center">
    <img width="450" src="/img/detect.gif">
</p>


Our project’s primary objective is to implement a technique for visual multi-face detection that not only yields accurate results but also exhibits minimal computational complexity. We utilized Haar features-based Adaboost Cascade Classifier, which combines classical image processing concepts with modern machine learning techniques to enable rapid and accurate multi-face detection. It utilizes the modern technique of "Integral Image Representation” for rapid computation of Haar features, subsequently used by Adaboost for classifier learning. We optimize a cascade of such strong classifiers for faster face detection.

<p align="center">
    <img width="480"  src="/img/Haar.png">
</p>

In the next phase of the project we integrated the Python code with a live webcam, enabling real-time face detection with the help of bounding boxes. We also compared its compution time with classical approaches such as Convolutional Neural Networks
