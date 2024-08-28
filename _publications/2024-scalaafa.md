---
title: "ScalaAFA: Constructing User-Space All-Flash Array Engine with Holistic Designs"
collection: publications
permalink: /publication/2024-scalaafa
excerpt: 'We propose ScalaAFA, a unique holistic design of AFA engine that can extend the throughput of next-generation SSD arrays in scale with low CPU costs. We incorporate ScalaAFA into user space to avoid user-kernel context switches while harnessing SSD built-in resources for handling AFA internal tasks…'
date: 2024-07-19
venue: 'USENIX Annual Technical Conference (ATC)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
All-flash array (AFA) is a popular approach to aggregate the capacity of multiple solid-state drives (SSDs) while guaranteeing fault tolerance. Unfortunately, existing AFA engines inflict substantial software overheads on the I/O path, such as the user-kernel context switches and AFA internal tasks (e.g., parity preparation), thereby failing to adopt next-generation high-performance SSDs.

Tackling this challenge, we propose ScalaAFA, a unique holistic design of AFA engine that can extend the throughput of next-generation SSD arrays in scale with low CPU costs. We incorporate ScalaAFA into user space to avoid user-kernel context switches while harnessing SSD built-in resources for handling AFA internal tasks. Specifically, in adherence to the lock-free principle of existing user-space storage framework, ScalaAFA substitutes the traditional locks with an efficient message-passing-based permission management scheme to facilitate inter-thread synchronization. Considering the CPU burden imposed by background I/O and parity computation, ScalaAFA proposes to offload these tasks to SSDs. To mitigate host-SSD communication overheads in offloading, ScalaAFA takes a novel data placement policy that enables transparent data gathering and in-situ parity computation. ScalaAFA also addresses two AFA intrinsic issues, metadata persistence and write amplification, by thoroughly exploiting SSD architectural innovations. Comprehensive evaluation results indicate that ScalaAFA can achieve 2.5x write throughput and reduce average write latency by a significant 52.7%, compared to the state-of-the-art AFA engines.

[Paper download](https://www.usenix.org/system/files/atc24-yi-shushu.pdf)

Recommended citation: Yi, Shushu, Xiurui Pan, Qiao Li, Qiang Li, Chenxi Wang, Bo Mao, Myoungsoo Jung, and Jie Zhang. "{ScalaAFA}: Constructing {User-Space}{All-Flash} Array Engine with Holistic Designs." In 2024 USENIX Annual Technical Conference (USENIX ATC 24), pp. 141-156. 2024.