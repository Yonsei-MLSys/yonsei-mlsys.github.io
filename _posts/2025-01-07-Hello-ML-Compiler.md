---
layout: post
title: DL Compiler and Compiler Optimization
---

**Kiung Jung**
- ASO Lab, Yonsei Univiersity

A compiler is a software tool that acts as an interface between the user and the hardware. DL models, like classical programs, cannot be directly executed on GPUs without the assistance of compilers. In this talk, we will explore various DL compiler optimizations, such as kernel fusion, and delve into the PyTorch software stack. Additionally, we will examine how the Triton language is transformed from a Python Domain Specific Language (DSL) into PTX.