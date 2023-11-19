---
layout: page
permalink: /Internship/
title: Internship
description:
nav: true
nav_order: 2
---

# *Google Silicon Engineering Intern* [[Presentation]](/assets/pdf/Presentation.pdf)
<p align="center">
    <img width="450"  src="/assets/img/intern.png">
</p>

Throughout my summer internship at Google as a Silicon Hardware intern, I was involved in four significant projects over the course of 10 weeks. In my first project, I conducted toggle coverage analysis using Python-based flows to extract exclusion files aimed at optimizing design verification. These exclusion files comprised tied-off or floating signals within the Device Under Test (DUT) and were utilized to exclude these specific signals during the verification process, effectively enhancing and streamlining the design verification procedure.
The refined files generated from this analysis were utilized to exclude these specific signals during the verification process, effectively enhancing and streamlining the design verification procedure.
<p align="center">
    <img width="450" height="300" src="/assets/img/smart_exclusion.png">
</p>

Additionally, I implemented the Smart Exclusion feature, automating the generation of exclusion files across all hierarchies using the design elaboration database. This integration further optimized the verification process, significantly reducing the time spent by users to exclude connected signals across multiple hierarchies.
<p align="center">
    <img width="450" src="/assets/img/flop.png">
</p>

In my subsequent task, I focused on implementing automated checkers for retaining flops during teardown and low-power mode applications. This involved generating a comprehensive list of internal flops declared across multiple System Verilog files. I then seamlessly integrated this file into the existing Change List, executed various test cases, and effectively troubleshooted encountered errors. For my final task, I developed a script to automate the parameter verification flow, enabling the identification of parameter value mismatches within the RTL files in the design.
errors in case of any mismatch, streamlining the verification process.
