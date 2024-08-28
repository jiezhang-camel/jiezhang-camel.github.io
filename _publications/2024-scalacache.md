---
title: "ScalaCache: Scalable User-Space Page Cache Management with Software-Hardware Coordination"
collection: publications
permalink: /publication/2024-scalacache
excerpt: 'We propose ScalaCache, a scalable user-space page cache with software-hardware coordination. Specifically, to reduce the host CPU overhead, we offload the cache management into computational SSDs (CSDs) and further merge the indirection layers in both the cache and flash firmware, which facilitates lightweight cache management…'
date: 2024-07-19
venue: 'USENIX Annual Technical Conference (ATC)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Due to the host-centric design principle, the existing page cache management suffers from CPU consumption, communication costs, and garbage collection (GC) interference. To address these challenges, we propose ScalaCache, a scalable user-space page cache with software-hardware coordination. Specifically, to reduce the host CPU overhead, we offload the cache management into computational SSDs (CSDs) and further merge the indirection layers in both the cache and flash firmware, which facilitates lightweight cache management. To further boost scalability, we build a lockless resource management framework that allows multiple CSD internal cores to manage the cache space concurrently. ScalaCache also aggregates the computing power of multiple CSDs to deliver scalable I/O performance. Moreover, ScalaCache reduces communication costs by trimming the I/O control path while mitigating GC interference via a GC-aware replacement policy, thereby enhancing its efficiency and performance stability. Our evaluation results reveal that ScalaCache exhibits 3.71x and 1.70x bandwidth improvements, respectively, compared to kernel page cache and the state-of-the-art user-space one.

[Paper download](https://www.usenix.org/system/files/atc24-peng.pdf)

Recommended citation: Peng, Li, Yuda An, You Zhou, Chenxi Wang, Qiao Li, Chuanning Cheng, and Jie Zhang. "{ScalaCache}: Scalable {User-Space} Page Cache Management with {Software-Hardware} Coordination." In 2024 USENIX Annual Technical Conference (USENIX ATC 24), pp. 1185-1202. 2024.