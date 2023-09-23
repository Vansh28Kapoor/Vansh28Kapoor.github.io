---
layout: page
title: "BIOMEDICAL IMAGE SEGMENTATION USING DEEP LEARNING"
permalink: /projects/Image-Segmentation/
---


  [_EE 610: Image Processing_](https://www.ee.iitb.ac.in/web/course_lists/ee-768-introduction-to-machine-learning/), [_Prof. Amit Sethi_](https://www.ee.iitb.ac.in/~asethi/)  
  
[Report](assets/pdf/Project_Report) | [Github](https://github.com/Vansh28Kapoor/BIOMEDICAL-IMAGE-SEGMENTATION-USING-DEEP-LEARNING) 


<br>
<p align="center">
    <img width="450"  src="/img/U-net.png">
</p>


The central aim of the project was to perform nuclei segmentation for breast tumor cells in histopathology images.
This was achieved through the utilization of a multi-organ transfer learning approach, specifically tailored to segment the nuclei of breast tumor cells. Coded a U-Net architecture tailored for binary semantic segmentation for distinguishing between nucleus and non-nucleus regions in stained tissue images by employing TensorFlow+Keras. The U-Net model was trained using Diceloss and the architecture was also modified the architecture to study the effects of changing the number of blocks and filters per layer.

<p align="center">
    <img width="250" height="250" src="/img/img_segmentation.gif">
</p>

In the next phase of the project Watershed Segmentation was applied on the probability map produced by U-Net for segmentation of individual nuclei and demonstrated its effectiveness on test images containing overlapping or touching nuclei.
