---
layout: page
title: "MULTI-FACETED IMAGE RESTORATION AND ENHANCEMENT"
---


  [_EE 610: Image Processing_](https://www.ee.iitb.ac.in/web/course_lists/ee-610-image-processing/), [_Prof. Amit Sethi_](https://www.ee.iitb.ac.in/~asethi/)  [[Github]](https://github.com/Vansh28Kapoor/MULTI-FACETED-IMAGE-RESTORATION-AND-ENHANCEMENT) 

<br>
<p align="center">
    <img height="300" src="/assets/img/Lena.gif">
</p>

Utilized the approach of Chen-et-al [Image Denoising using Neighbouring Wavelet Coefficients](https://www.egr.msu.edu/~aviyente/neighshrink.pdf) to effectively for practical image denoising applications. This approach utilizes the correlations between neighboring wavelet coefficients, i.e., a large wavelet coefficient will probably have large
wavelet coefficients as its neighbour.

<p align="center">
    <img  width="400"  src="/assets/img/Motion_deblur.gif">
</p>
Predicted and implemented the motion blur kernel by utilizing the angle of smear present in motion-blurred car images to give the direction of motion blur. Finally, performed Weiner filtering using the estimated blurring kernel to effectively reveal the license plate characters in these shaky images of cars.
<br>
<br>

<p align="center">
    <img height="300" src="/assets/img/Triton.gif">
</p>
Performed satellite image restoration by removing subtle scanning artifacts of one of the images taken by Voyager 2 by filtering the images piecewise in the Fourier domain. Revealed intricate details by histogram manipulation while simultaneously maintaining color balance. 
<br>
<br>
<p align="center">
    <img height="300" src="/assets/img/Moire.gif">
</p>
Performed filtering in the Fourier domain to remove the high-frequency components along the vertical and horizontal directions thus eliminating the moiré effect.
