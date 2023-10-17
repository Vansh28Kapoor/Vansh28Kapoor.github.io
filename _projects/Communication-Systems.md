---
layout: page
title: "Implementation Of Communication Systems"
permalink: /projects/Communication-Systems/
---

  [_EE 340: Communications Laboratory_](https://www.ee.iitb.ac.in/web/course_lists/ee-340-communications-laboratory/), [_Prof. Jayakrishnan Nair_](https://www.ee.iitb.ac.in/~jayakrishnan.nair/) 

## 1. Practical Modulation Of RF signals 
<p align="center">
    <img width="450"  src="/assets/img/IQ-modulator.png">
</p>

Performed practical analysis of analog carrier modulation schemes (DSB, DSB-SC, and SSB) using an IQ modulator board and AFG by observing the received spectrum using GNU Radio and a dongle. Verified the effects of of amplitude and phase imbalances in Side Band Suppression (SSB) by varying the amplitude and phase differences between I and Q signals.

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
