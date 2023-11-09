---
layout: page
title: "Implementation Of Control Systems"
permalink: /projects/Control-Systems/
---

_Lab Project for EE324: Control systems lab_  

<div style="display: flex;">
    <a href="/assets/pdf/Controls.pdf" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">Report</div>
    </a>
    <a href="https://github.com/Vansh28Kapoor/Control-Systems" style="flex: 1; padding: 10px; border: 1px solid grey; text-align: center; text-decoration: none;">
        <div style="font-weight: bold; color: orchid;">GitHub</div>
    </a>
</div>

<br>

## 1. Line Following Robot
<p align="center">
    <img width="450" height="250" src="/assets/img/Line_follower.gif">
</p>

Designed and implemented a PID controller for a line follower Spark V robot that can make it transverse a given sample path within 30 seconds. The derivative component of the PID controller enabled the bot to execute sharp turns and apply corrective measures in the event of gentle or incorrect turns, while the proportional component of the PID controller primarily served to oversee the bot's speed. The PID controller recieved its input from the three sensors situated on the bot's underside and using this information it independently regulated the speed of both the left and right wheels. 

## 2. Active Noise-Cancellation in Headphones
<br>
<p align="center">
    <img width="450" height="250" src="/assets/img/headphones.gif">
</p>
The objective of the experiment was to design and integrate an active noise-cancellation circuit into a pair of headphones, with the goal of achieving a 20dB reduction in noise when exposed to a 100Hz frequency sound source. Through our design process and MATLAB analysis, we carefully crafted a lead-lag compensator with precisely tuned parameters, ensuring it aligns with our primary objective of reducing noise by a minimum of 20dB. The designed compensator achieved a gain margin of 10.2 dB and phase margin of 50° to ensure robustness.  In practical testing with a 100Hz noise source, it showcased an impressive attenuation of 20.2 dB.

## 3. DC Motor Position Control
<br>
<p align="center">
    <img width="450" height="250" src="/assets/img/DC-motor.png">
</p>
The experiment aimed to achieve precise DC motor position control by designing and implementing an embedded PID feedback controller. This controller was created using an Arduino Mega and a motor driver circuit, with the goal of achieving a rise-time of less than 0.5 sec, a 1-second settling time, and an overshoot of atmost 10%.
