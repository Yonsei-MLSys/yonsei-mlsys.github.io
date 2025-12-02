---
layout: post
title: "Accelerating Diffusion Model via Inherent Characteristic of Diffusion Process"
---

<h5>
    Sungbin Kim - eSCaL, EE, Yonsei University
</h5>

This presentation provides an overview of the characteristics of diffusion models and introduces acceleration techniques and accelerator architectures that leverage their inherent properties. We analyze the iterative structure of diffusion models and observe that adjacent time steps exhibit strong value similarity, resulting in small differences between consecutive steps. By applying this observation to quantized diffusion models, we show that most of these differences can be represented using reduced bit-width—or even zero.

Building on these insights, we propose Ditto, a temporal difference–based processing algorithm that exploits temporal similarity under quantization to improve the efficiency of diffusion model execution. Ditto performs full–bit width computation only at the initial time step and processes subsequent steps using temporal differences through the distributive property of layer operations. Furthermore, we introduce an execution–flow optimization that reduces the memory overhead associated with temporal difference processing, further enhancing overall efficiency. Finally, we present Ditto Hardware, a specialized accelerator designed to fully exploit the dynamic characteristics of the proposed algorithm.

[PPT](https://drive.google.com/file/d/1vEhUqSdaqlNiEzZm8AbsB87sBidJJdke/view?usp=share_link)
[CV](https://drive.google.com/file/d/1WOigwiy1R8_foR0iqIZh9dgVxp6GKq7s/view?usp=share_link)

<i>
    Catering Courtesy of <a href="https://sites.google.com/view/asolabysu/home">ASO Lab</a>
    <br>
    Invited Talk
</i>
