---
layout: page
title: "Biomedical Image Segmentation Using Deep Learning"
permalink: /projects/Image-Segmentation/
---


  [_EE 610: Image Processing_](https://www.ee.iitb.ac.in/web/course_lists/ee-610-image-processing/), [_Prof. Amit Sethi_](https://www.ee.iitb.ac.in/~asethi/)
  
<div style="display: flex;">
    <a href="https://github.com/Vansh28Kapoor/BIOMEDICAL-IMAGE-SEGMENTATION-USING-DEEP-LEARNING" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">GitHub</div>
    </a>
</div>
      
<br>

<p align="center">
    <img width="450"  src="/img/U-net.png">
</p>


The central aim of the project was to perform nuclei segmentation for breast tumor cells in histopathology images.
This was achieved through the utilization of a multi-organ transfer learning approach, specifically tailored to segment the nuclei of breast tumor cells. Coded a U-Net architecture tailored for binary semantic segmentation for distinguishing between nucleus and non-nucleus regions in stained tissue images by employing TensorFlow+Keras. The U-Net model was trained using Diceloss and the architecture was also modified the architecture to study the effects of changing the number of blocks and filters per layer.

<p align="center">
    <img width="250" height="250" src="/assets/img/Bio.gif">
</p>

In the next phase of the project Watershed Segmentation was applied to the probability map produced by U-Net for segmentation of individual nuclei and demonstrated its effectiveness on test images containing overlapping or touching nuclei.
