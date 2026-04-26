---
layout: post
title: "Preserve-Then-Quantize"
---


<h5>
    Yoonjun Cho - AI-ISL, CS, Yonsei University
</h5>

Low-bit quantization of large language models often suffers from reconstruction error, as prior methods like QER allocate all low-rank capacity to error approximation while neglecting dominant structure. We propose Structured Residual Reconstruction (SRR), which splits a fixed rank budget between preserving key subspace directions and reconstructing quantization error via a principled one-shot criterion. This captures the trade-off without costly search. Empirically, SRR outperforms QER, integrates with GPTQ and QUIP#, and provides strong initialization for QPEFT, highlighting the importance of balancing preservation and reconstruction.

<!-- [PPT](https://drive.google.com/file/d/1kANUhMbtxmFsYG7GXdBnwnAEmOmpdwQi/view?usp=share_link) -->
[CV](https://cyoonjun.github.io/)

<i>
    Catering Courtesy of <a href="https://www.ciplab.kr/">CIP Lab</a>
</i>