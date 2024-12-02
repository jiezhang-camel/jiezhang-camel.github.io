---
title: "FlashLLM: A Chiplet-Based In-Flash Computing Architecture to Enable On-Device Inference of 70B LLM"
collection: publications
permalink: /publication/2024-flashllm
excerpt: 'we introduce FlashLLM, a chiplet-based hybrid architecture designed for on-device inference of 70B LLM. FlashLLM features a dedicated flash chip connected directly to NPU through chiplet technology.
The flash not only stores model weight matrices but also leverages on-die processing capabilities to reduce data transfers to NPU, thereby mitigating both the footprint and bandwidth limitations. The NPU, in addition to collaborating with flash for matrix operations…'
date: 2024-11-01
venue: 'IEEE/ACM International Symposium on Microarchitecture (MICRO)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
The deployment of powerful Large Language Models (LLMs) as AI assistants on edge devices such as smartphones and vehicles represents a future trend, offering enhanced privacy of user data and independence from network connectivity. Nevertheless, the deployment of LLMs necessitates an extensive parameter set, posing significant challenges for integration into edge devices. This has triggered abundant research into the offloading of LLM weights onto flash-based storage. However, the limited bandwidth of flash memory significantly hampers inference speed, especially in edge inference scenarios where the batch size is 1 and the arithmetic intensity can be as minimal as 2.

To address these issues, we introduce FlashLLM, a chiplet-based hybrid architecture designed for on-device inference of 70B LLM. FlashLLM features a dedicated flash chip connected directly to NPU through chiplet technology.
The flash not only stores model weight matrices but also leverages on-die processing capabilities to reduce data transfers to NPU, thereby mitigating both the footprint and bandwidth limitations. The NPU, in addition to collaborating with flash for matrix operations, is also responsible for managing the key-value cache (KV cache) in DRAM and performing special function computations that exceed the on-die processing capabilities of the flash. Overall, FlashLLM enables the on-device inference of 70B LLMs at a speed of 3.44 token/s, and 7B LLMs at a speed of 36.34 token/s, which is over 22× to 45× faster than existing flash-offloading technologies.

[Paper download](https://arxiv.org/abs/2409.15654)

Recommended citation: .