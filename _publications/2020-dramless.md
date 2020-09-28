---
title: "DRAM-less: Hardware Acceleration of Data Processing with New Memory"
collection: publications
permalink: /publication/2020-dramless
excerpt: 'In this work, we propose, DRAM-less, a hardware automation approach that precisely integrates many state-of-the-art phase change memory (PRAM) modules into its data processing network to dramatically reduce unnecessary data copies with a minimum of software modifications. We implement a new memory controller that plugs a real 3x nm multi-partition PRAM to 28nm technology FPGA logic cells and interoperate its design into a real PCIe accelerator emulation platform…'
date: 2020-03-01
venue: 'International Symposium on High Performance Computer Architecture (HPCA)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
General purpose hardware accelerators have become major data processing resources in many computing domains. However, the processing capability of hardware accelerations is often limited by costly software interventions and memory copies to support compulsory data movement between different processors and solid-state drives (SSDs). This in turn also wastes a significant amount of energy in modern accelerated systems. In this work, we propose, DRAM-less, a hardware automation approach that precisely integrates many state-of-the-art phase change memory (PRAM) modules into its data processing network to dramatically reduce unnecessary data copies with a minimum of software modifications. We implement a new memory controller that plugs a real 3x nm multi-partition PRAM to 28nm technology FPGA logic cells and interoperate its design into a real PCIe accelerator emulation platform. The evaluation results reveal that our DRAM-less achieves, on average, 47% better performance than advanced acceleration approaches that use a peer-to-peer DMA.

[Paper download](https://ieeexplore.ieee.org/document/9065582)

Recommended citation: Zhang, Jie, Gyuyoung Park, David Donofrio, John Shalf, and Myoungsoo Jung. "DRAM-Less: Hardware Acceleration of Data Processing with New Memory." In 2020 IEEE International Symposium on High Performance Computer Architecture (HPCA), pp. 287-302. IEEE, 2020.