---
title: "NVMMU: A Non-Volatile Memory Management Unit for Heterogeneous GPU-SSD Architectures"
collection: publications
permalink: /publication/2016-nvme
excerpt: 'In this work, NVMMU unifies two discrete software stacks (one for the SSD and other for the GPU) in two major ways. While a new interface provided by our NVMMU directly forwards file data between the GPU runtime library and the I/O runtime library, it supports non-volatile direct memory access (NDMA) that pairs those GPU and SSD devices via physically shared system memory blocks. This unification in turn can eliminate unnecessary user/kernel-mode switching, improve memory management, and remove data copy overheads…'
date: 2015-10-01
venue: 'International Conference on Parallel Architectures and Compilation Techniques (PACT)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Thanks to massive parallelism in modern Graphics Processing Units (GPUs), emerging data processing applications in GPU computing exhibit ten-fold speedups compared to CPU-only systems. However, this GPU-based acceleration is limited in many cases by the significant data movement overheads and inefficient memory management for host-side storage accesses. To address these shortcomings, this paper proposes a non-volatile memory management unit (NVMMU) that reduces the file data movement overheads by directly connecting the Solid State Disk (SSD) to the GPU. We implemented our proposed NVMMU on a real hardware with commercially available GPU and SSD devices by considering different types of storage interfaces and configurations. In this work, NVMMU unifies two discrete software stacks (one for the SSD and other for the GPU) in two major ways. While a new interface provided by our NVMMU directly forwards file data between the GPU runtime library and the I/O runtime library, it supports non-volatile direct memory access (NDMA) that pairs those GPU and SSD devices via physically shared system memory blocks. This unification in turn can eliminate unnecessary user/kernel-mode switching, improve memory management, and remove data copy overheads. Our evaluation results demonstrate that NVMMU can reduce the overheads of file data movement by 95% on average, improving overall system performance by 78% compared to a conventional IOMMU approach.

[Download paper here](http://camelab.org/uploads/Main/nvmmu-jung.pdf)

Recommended citation: Zhang, Jie, David Donofrio, John Shalf, Mahmut T. Kandemir, and Myoungsoo Jung. "Nvmmu: A non-volatile memory management unit for heterogeneous gpu-ssd architectures." In 2015 International Conference on Parallel Architecture and Compilation (PACT), pp. 13-24. IEEE, 2015.