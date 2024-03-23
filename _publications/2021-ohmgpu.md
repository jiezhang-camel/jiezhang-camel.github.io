---
title: "Ohm-GPU: Integrating New Optical Network and Heterogeneous Memory into GPU Multi-Processors"
collection: publications
permalink: /publication/2021-ohmgpu
excerpt: 'We propose Ohm-GPU, a new optical network based heterogeneous memory design for GPUs. Specifically, Ohm-GPU can expand the memory capacity by combing a set of high-density 3D XPoint and DRAM modules as heterogeneous memory. To prevent memory channels from throttling throughput of GPU memory system, Ohm-GPU replaces the electrical lanes in the traditional memory channel with a high-performance optical network…'
date: 2021-10-01
venue: 'IEEE/ACM International Symposium on Microarchitecture (MICRO)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Traditional graphics processing units (GPUs) suffer from the low memory capacity and demand for high memory bandwidth. To address these challenges, we propose Ohm-GPU, a new optical network based heterogeneous memory design for GPUs. Specifically, Ohm-GPU can expand the memory capacity by combing a set of high-density 3D XPoint and DRAM modules as heterogeneous memory. To prevent memory channels from throttling throughput of GPU memory system, Ohm-GPU replaces the electrical lanes in the traditional memory channel with a high-performance optical network. However, the hybrid memory can introduce frequent data migrations between DRAM and 3D XPoint, which can unfortunately occupy the memory channel and increase the optical network traffic. To prevent the intensive data migrations from blocking normal memory services, Ohm-GPU revises the existing memory controller and designs a new optical network infrastructure, which enables the memory channel to serve the data migrations and memory requests, in parallel. Our evaluation results reveal that Ohm-GPU can improve the performance by 181% and 27%, compared to a DRAMbased GPU memory system and the baseline optical network based heterogeneous memory system, respectively.

[Paper download](https://doi.org/10.1145/3466752.3480107)

Recommended citation: Zhang, Jie, and Myoungsoo Jung. "Ohm-GPU: integrating new optical network and heterogeneous memory into gpu multi-processors." In MICRO-54: 54th Annual IEEE/ACM International Symposium on Microarchitecture, pp. 695-708. 2021.