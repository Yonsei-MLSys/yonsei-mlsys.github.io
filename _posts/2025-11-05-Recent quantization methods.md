---
layout: post
title: "Recent quantization methods"
---

<h5>
    Yoonjun Cho - AI-ISL, CS, Yonsei University
</h5>

This seminar reviews recent advances in low-bit quantization for LLMs. It revisits GPTQ as the standard activation-aware, post-training method, noting its layer-wise design and the gap between weight and output error minimization. GPTAQ refines this with asymmetric calibration that blends original and quantized activations to mitigate accumulated errors, aligning with rotation-based designs like QuaRot. Finally, ParetoQ analyzes scaling laws over model size, token budget, and bit-width, showing that 2-bit and ternary models yield efficient accuracy–speed–memory trade-offs.

[PPT](https://drive.google.com/file/d/1VmwwcssKcYIpN6DpBFt5QnNNqqBa8C81/view?usp=sharing)
[CV](https://cyoonjun.github.io/)

<i>
    Catering Courtesy of <a href="https://albert-no.github.io/">AI-ISL</a>
</i>
