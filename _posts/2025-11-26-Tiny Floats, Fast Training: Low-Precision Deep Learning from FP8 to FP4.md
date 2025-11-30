---
layout: post
title: "Tiny Floats, Fast Training: Low-Precision Deep Learning from FP8 to FP4"
---

<h5>
    Kanghyun Choi - AISys, EE, Seoul National University
</h5>

TL;DR: FP8 and FP4 accelerate deep learning only if quantization overhead is addressed; FALQON restructures fine-tuning to recover those speedups.

This talk provides an overview of low-precision floating-point formats used in GPU-based deep learning, with a focus on FP8 and FP4 as supported in recent NVIDIA architectures. It discusses how these formats enable efficient quantization, how scaling affects representable ranges, and where performance gains appear or disappear in real workloads. The second part introduces FALQON, a quantization-aware fine-tuning method that avoids the overhead typically seen when applying FP8 to LoRA modules. The goal is to provide both conceptual grounding and a concrete example of algorithm design for efficient low-precision LLM fine-tuning.

[PPT](https://drive.google.com/file/d/1fV_hOqvf7D9vziEZRSMwJ6liGDoSUtoY/view?usp=share_link)
[CV](https://drive.google.com/file/d/12H05yhvg4zamk0mWikSXa5tBQ_LI3KTS/view?usp=share_link)

<i>
    Catering Courtesy of <a href="https://sites.google.com/view/asolabysu/home">ASO Lab</a>
</i>
