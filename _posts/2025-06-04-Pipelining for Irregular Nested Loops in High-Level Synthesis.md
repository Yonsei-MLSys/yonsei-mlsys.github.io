---
layout: post
title: "Pipelining for Irregular Nested Loops in High-Level Synthesis"
---

<h5>
    Kunmo Jeong - CoreLab, EE, Yonsei University
</h5>

The growing demand for domain-specific accelerators in fields such as machine learning, graph analytics, and scientific computing has highlighted the need for productive and efficient hardware design methodologies. High-level synthesis (HLS) offers an attractive solution by generating hardware circuits from high-level code, with loop pipelining serving as a cornerstone for maximizing throughput in regular computations. However, existing static and dynamic HLS approaches fail to achieve high pipeline utilization for irregular loop nests that are characterized by data-dependent bounds, unpredictable memory access patterns, and loop-carried dependencies.

To address the pipeline underutilization in irregular loop, this work proposes a new barrier-free pipeline architecture with a cross-level scheduling strategy and the corresponding HLS compiler Selene, that automatically synthesizes the proposed architecture.
Our approach introduces a fine-grained pipeline controller and an outer-loop iteration interleaving mechanism, enabling concurrent execution of multiple outer-loop iterations and efficient handling of data dependencies. Implemented within a commercial HLS flow, Vitis HLS, Selene delivers significant speedups of 5.21x and 5.68x over both standard static and dynamic HLS tools on a range of irregular workload benchmarks, demonstrating its effectiveness in overcoming longstanding barriers to efficient hardware generation for data-dependent applications.

[PPT](https://drive.google.com/file/d/1x2EkGoLPB8is-QtqEDGAvQs0tgkb6hQk/view?usp=share_link)
[CV](https://drive.google.com/file/d/1IG1NWoyJ24GH4STSgbjlvPzWq7McVdJ2/view?usp=sharing)

<i>
    Catering Courtesy of <a href="https://www.ciplab.kr/">CIP Lab</a>
</i>
