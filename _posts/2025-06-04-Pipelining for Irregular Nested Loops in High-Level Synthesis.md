---
layout: post
title: "Pipelining for Irregular Nested Loops in High-Level Synthesis"
---

<h5>
    Kunmo Jeong - CoreLab, EE, Yonsei University
</h5>

As digital systems grow increasingly complex, traditional Register Transfer Level (RTL) design using Hardware Description Languages (HDLs) such as Verilog or VHDL has become increasingly labor-intensive, error-prone, and time-consuming. To address these challenges, High-Level Synthesis (HLS) has emerged as a promising paradigm, enabling designers to describe hardware behavior using high-level programming languages like C/C++, and automatically translating them into RTL implementations. This presentation examines the motivations for adopting HLS in modern digital circuit design, outlining its key advantages such as improved design productivity, faster verification, and enhanced maintainability. However, HLS also brings limitations, including reduced control over low-level optimizations and unpredictable performance for irregular computation patterns.
A particular focus is placed on the challenges and opportunities of applying HLS to irregular nested loops, which frequently occur in domains such as image processing, scientific computing, and sparse linear algebra. These loop structures pose significant optimization difficulties due to their data-dependent control flows and variable iteration bounds. We explore current techniques for addressing these challenges, including loop restructuring, dependency analysis, and memory access optimization. Finally, the presentation discusses ongoing research directions that aim to extend HLS capabilities to better support irregular computations, offering insight into its long-term potential as a general-purpose hardware design methodology.

[PPT](https://drive.google.com/file/d/1x2EkGoLPB8is-QtqEDGAvQs0tgkb6hQk/view?usp=share_link)
[CV](https://drive.google.com/file/d/1IG1NWoyJ24GH4STSgbjlvPzWq7McVdJ2/view?usp=sharing)

<i>
    Catering Courtesy of <a href="https://www.ciplab.kr/">CIP Lab</a>
</i>
