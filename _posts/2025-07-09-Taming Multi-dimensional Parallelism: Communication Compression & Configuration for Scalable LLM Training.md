---
layout: post
title: "Taming Multi-dimensional Parallelism: Communication Compression & Configuration for Scalable LLM Training"
---

<h5>
    Jayong Song - AISys, EE, Seoul National University
</h5>

Training today’s large language models (LLMs) demands thousands of GPUs orchestrated with multi-dimensional parallelism such as 3D/5D parallelism.
This talk brings together two complementary systems that remove the twin roadblocks such scale introduces:

1) Optimus-CC attacks the communication bottleneck. It aggressively compresses not only data-parallel traffic but also pipeline back-propagation signals and embedding synchronizations. Error-suppression techniques—grounded in formal analysis—preserve model quality while selectively compressing only critical-path transfers, yielding state-of-the-art speedups on multi-node clusters.

2) Pipette tackles the configuration bottleneck. It automatically finds memory-safe 3D-parallel splits and GPU mappings by modeling real-world, link-level bandwidth heterogeneity and per-GPU memory limits. The resulting configurations execute—and accelerate—LLM training where prior tuners stall or underperform.

Together, Optimus-CC and Pipette show that principled communication compression and topology-aware configuration are both necessary and synergistic for unlocking fast, memory-efficient, and scalable LLM training.
I want to share the key algorithmic insights of the above papers and some details of recent parallelism with Mixture-of-Expert (MoE) models for future research.

<!-- [PPT](https://docs.google.com/presentation/d/1wng-Hd4IH1ve9msz-gc3WjvzOWVxBJiz/edit?usp=share_link&ouid=111948851444227468135&rtpof=true&sd=true) -->
[CV](https://drive.google.com/file/d/1LckkOslFFCAfksnh6m8UHC7SoGLHESq9/view?usp=sharing)

<i>
    Catering Courtesy of <a href="https://micv.yonsei.ac.kr/">MICV Lab</a>
    <br>
    Invited Talk
</i>