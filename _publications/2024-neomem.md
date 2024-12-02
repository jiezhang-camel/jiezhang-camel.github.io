---
title: "NeoMem: Hardware/Software Co-Design for CXL-Native Memory Tiering"
collection: publications
permalink: /publication/2024-neomem
excerpt: 'we propose a novel memory tiering solution called NeoMem, which features a hardware/software co-design. NeoMem offloads memory profiling functions to CXL device-side controllers…'
date: 2024-11-01
venue: 'IEEE/ACM International Symposium on Microarchitecture (MICRO)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
The Compute Express Link (CXL) interconnect makes it feasible to integrate diverse types of memory into servers via its byte-addressable SerDes links. Considering the various access latency, harnessing the full potential of CXL-based heterogeneous memory systems requires efficient memory tiering. However, prior work can hardly make a fundamental progress owing to low-resolution and high-overhead memory access profiling techniques. To address this critical challenge, we propose a novel memory tiering solution called NeoMem, which features a hardware/software co-design. NeoMem offloads memory profiling functions to CXL device-side controllers, integrating a dedicated hardware unit called NeoProf. NeoProf readily monitors memory accesses and provides the OS with crucial page hotness statistics and other useful system state information. On the OS kernel side, we design a revamped memory-tiering strategy, enabling accurate and timely hot page promotion based on NeoProf statistics. We implement NeoMem on a real FPGA-based CXL memory platform and Linux kernel v6.3. Comprehensive evalu- ations demonstrate that NeoMem achieves 32% ∼ 67% geomean speedup over several existing memory tiering solutions.

[Paper download](https://arxiv.org/abs/2403.18702)

Recommended citation: .