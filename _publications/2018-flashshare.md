---
title: "FlashShare: Punching Through Server Storage Stack from Kernel to Firmware for Ultra-Low Latency SSDs"
collection: publications
permalink: /publication/2018-flashshare
excerpt: 'In this paper, we propose FlashShare to assist ULL SSDs to satisfy different levels of I/O service latency requirements for different co-running applications. Specifically, FlashShare is a holistic cross-stack approach, which can significantly reduce I/O interferences among co-running applications at a server without any change in applications. At the kernel-level, we extend the data structures of the storage stack to pass attributes of (co-running) applications through all the layers of the underlying storage stack spanning from the OS kernel to the SSD firmware…'
date: 2018-10-01
venue: '13th USENIX Symposium on Operating Systems Design and Implementation (OSDI)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
A modern datacenter server aims to achieve high energy efficiency by co-running multiple applications. Some of such applications (e.g., web search) are latency sensitive. Therefore, they require low-latency I/O services to fast respond to requests from clients. However, we observe that simply replacing the storage devices of servers with Ultra-Low-Latency (ULL) SSDs does not notably reduce the latency of I/O services, especially when co-running multiple applications. In this paper, we propose FlashShare to assist ULL SSDs to satisfy different levels of I/O service latency requirements for different co-running applications. Specifically, FlashShare is a holistic cross-stack approach, which can significantly reduce I/O interferences among co-running applications at a server without any change in applications. At the kernel-level, we extend the data structures of the storage stack to pass attributes of (co-running) applications through all the layers of the underlying storage stack spanning from the OS kernel to the SSD firmware. For given attributes, the block layer and NVMe driver of FlashShare differently manage the I/O scheduler and interrupt handler of NVMe. We also enhance the NVMe controller and cache layer at the SSD firmware-level, by dynamically partitioning DRAM in the ULL SSD and adjusting its caching strategies to meet diverse user requirements. The evaluation results demonstrate that FlashShare can shorten the average and 99th-percentile turnaround response times of co-running applications by 22% and 31%, respectively.

[Paper download](https://arxiv.org/pdf/1811.01544.pdf)

Recommended citation: Zhang, Jie, Miryeong Kwon, Donghyun Gouk, Sungjoon Koh, Changlim Lee, Mohammad Alian, Myoungjun Chun et al. "FlashShare: Punching through server storage stack from kernel to firmware for ultra-low latency SSDs." In 13th {USENIX} Symposium on Operating Systems Design and Implementation ({OSDI} 18), pp. 477-492. 2018.