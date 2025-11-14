---
layout: post
title: "Safety Alignment for Language Models: From Shallow to Deep across Diverse Strategies"
---

<h5>
    Wonje Jeung - AI-ISL, AI, Yonsei University
</h5>

Recent work has shown that safety alignment in large language models (LLMs) is often shallow, degrading after just a few output tokens. The ICLR 2025 best paper, “Safety Alignment Should Not Be Just a Few Tokens Deep,” reveals how autoregressive models fail to reject harmful content beyond the initial decoding steps. While that work focuses on left-to-right generation, diffusion language models (dLLMs) have recently gained attention for their flexible and parallel decoding, which improves efficiency but introduces new safety vulnerabilities. Unlike autoregressive models, dLLMs generate tokens in any order, allowing them to decode arbitrary positions in the sequence and to intervene in the generation process at any step, meaning alignment must hold throughout the entire iterative generation process. This makes shallow alignment particularly dangerous, as harmful spans may emerge late and unpredictably. In this talk, we introduce A2D (Any-order, Any-step Defense), a token-level alignment method designed for dLLMs. A2D supervises the model to emit an early [EOS] token at high-risk masked positions, enabling robust rejection of unsafe content regardless of where or when it appears. Our results show that A2D successfully defends against strong attacks such as DIJA and FITS, while maintaining benign usability, offering a practical path toward robust and interpretable safety alignment in dLLMs.

[PPT](https://docs.google.com/presentation/d/1qrrUp00X3wvmGSsVKVxN_-hOKbedxfqY/edit?usp=sharing&ouid=111948851444227468135&rtpof=true&sd=true)
[CV](https://drive.google.com/file/d/1nv4hYaR9thk7ABIOq4CDKVIqk31t1qdM/view?usp=sharing)

<i>
    Catering Courtesy of <a href="http://corelab.or.kr/index.php">CoreLab</a>
</i>

