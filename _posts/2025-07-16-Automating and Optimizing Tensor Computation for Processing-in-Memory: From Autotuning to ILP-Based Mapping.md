---
layout: post
title: "Automating and Optimizing Tensor Computation for Processing-in-Memory: From Autotuning to ILP-Based Mapping"
---

<h5>
    Hyeoncheol Kim - ASO Lab, CS, Yonsei University
</h5>

Processing-in-Memory (PIM) architectures offer a compelling approach to addressing the memory wall by enabling computation directly within memory units, thereby minimizing data movement. However, extracting meaningful performance gains from such architectures requires sophisticated software support capable of managing the tight coupling between data layout, computation scheduling, and hardware constraints.
This presentation explores two complementary system-level approaches designed to enhance the programmability and efficiency of PIM architectures. The first approach introduces a tensor compiler that integrates autotuning into the code generation pipeline for DRAM-based PIM systems. By jointly exploring optimization spaces across host and kernel levels, and applying PIM-aware transformations, this compiler automates the generation of efficient tensor programs.
The second approach formulates the tensor mapping problem for PIM as an integer linear programming (ILP) model. Leveraging a layout-aware representation and accurate cost modeling, this method produces optimized mappings that respect the unique data placement and execution constraints of various PIM architectures. Implemented within a modern compiler infrastructure, the framework supports end-to-end mapping from high-level deep learning workloads.
Together, these systems demonstrate how compiler-based autotuning and formal optimization techniques can significantly advance the usability and performance of PIM system.

[PPT](https://drive.google.com/file/d/11NeyYGH-8w8TYIL47VGFsv8yO1ZgjzvE/view?usp=sharing)
[CV](https://www.linkedin.com/in/hyeoncheol-kim-8a2337285)

<i>
    Catering Courtesy of <a href="https://micv.yonsei.ac.kr/">MICV Lab</a>
</i>
