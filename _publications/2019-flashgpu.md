---
title: "FlashGPU: Placing New Flash Next to GPU Cores"
collection: publications
permalink: /publication/2019-flashgpu
excerpt: 'We propose FlashGPU, a new GPU architecture that tightly blends new flash (Z-NAND) with massive GPU cores. Specifically, we replace global memory with Z-NAND that exhibits ultra-low latency. We also architect a flash core to manage request dispatches and address translations underneath L2 cache banks of GPU cores…'
date: 2019-06-01
venue: 'The 56th Design Automation Conference (DAC)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
We propose FlashGPU, a new GPU architecture that tightly blends new flash (Z-NAND) with massive GPU cores. Specifically, we replace global memory with Z-NAND that exhibits ultra-low latency. We also architect a flash core to manage request dispatches and address translations underneath L2 cache banks of GPU cores. While Z-NAND is a hundred times faster than conventional 3D-stacked flash, its latency is still longer than DRAM. To address this shortcoming, we propose a dynamic page-placement and buffer manager in Z-NAND subsystems by being aware of bulk and parallel memory access characteristics of GPU applications, thereby offering high-throughput and low-energy consumption behaviors.

[Paper download](https://ieeexplore.ieee.org/document/8806844)

Recommended citation: Zhang, Jie, Miryeong Kwon, Hyojong Kim, Hyesoon Kim, and Myoungsoo Jung. "FlashGPU: Placing New Flash Next to GPU Cores." In 2019 56th ACM/IEEE Design Automation Conference (DAC), pp. 1-6. IEEE, 2019.