---
layout: page
title: "Implementatio Of Control Systems"
permalink: /projects/Control-Systems/
---
_Lab Project for EE324: Control systems lab_  

<div style="display: flex;">
    <a href="/assets/pdf/Controls.pdf" style="flex: 1; padding: 10px; border: 1px solid #000; text-align: center; text-decoration: none;">
        <div style="font-weight: bold;">Report</div>
    </a>
    <a href="https://github.com/Vansh28Kapoor/Control-Systems" style="flex: 1; padding: 10px; border: 1px solid #000; text-align: center; text-decoration: none;">
        <div style="font-weight: bold;">GitHub</div>
    </a>
</div>

<br>
<p align="center">
    <img height="250" src="/assets/img/Line_follower.gif">
</p>

Designed and implemented a PID controller for a line follower Spark V robot that can make it transverse a given sample path within 30 seconds. The derivative component of the PID controller enabled the bot to execute sharp turns and apply corrective measures in the event of gentle or incorrect turns, while the proportional component of the PID controller primarily served to oversee the bot's speed. The PID controller recieved its input from the three sensors situated on the bot's underside and using this information it independently regulated the speed of both the left and right wheels. 
