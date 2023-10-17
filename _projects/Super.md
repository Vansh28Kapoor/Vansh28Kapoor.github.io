---
layout: page
title: Superscalar Processor Design
description: Designed a 2-way fetch out-of-order superscalar processor in VHDL
img: /assets/img/risc.PNG
importance: 1
category: "Technical Projects"
related_publications:
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/superscalar.png" title="Superscalar Processor" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of a Superscalar processor pipeline
</div>
</center>

_Guide: [Prof. Virendra Singh](https://www.ee.iitb.ac.in/~viren/)_  

This was a course project as part of the course CS683: Advanced Computer Architecture taught by Prof. Virendra Singh. The project involved designing a 2-way fetch OoO Superscalar processor, capable of running a Turing-complete ISA of 17 instructions. The architecture was complete with key components such as the Reservation Station, Reorder Buffer, Execution pipelines, Register Renaming, and the Memory System, all implemented in VHDL. My team conducted thorough software testing for all 17 instructions using GHDL and GTKWave simulations, and a custom testbench. We also created an Assembler and a Bootloader in Python to ease the process of dumping user instructions into the memory of the processor.

&nbsp;&nbsp;&nbsp;&nbsp; [GitHub](https://github.com/AnubhavBhatla/Superscalar-Processor){: .btn--github}
