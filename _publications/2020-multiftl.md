---
title: "Scalable Parallel Flash Firmware for Many-core Architectures"
collection: publications
permalink: /publication/2020-multiftl
excerpt: 'We propose DeepFlash, a novel manycore-based storage platform that can process more than a million I/O requests in a second (1MIOPS) while hiding long latencies imposed by its internal flash media. Inspired by a parallel data analysis system, we design the firmware based on many-to-many threading model that can be scaled horizontally. The proposed DeepFlash can extract the maximum performance of the underlying flash memory complex by concurrently executing multiple firmware components across many cores within the device…'
date: 2020-03-01
venue: 'USENIX Conference on File and Storage Technologies (FAST)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
NVMe is designed to unshackle flash from a traditional storage bus by allowing hosts to employ many threads to achieve higher bandwidth. While NVMe enables users to fully exploit all levels of parallelism offered by modern SSDs, current firmware designs are not scalable and have difficulty in handling a large number of I/O requests in parallel due to its limited computation power and many hardware contentions.

We propose DeepFlash, a novel manycore-based storage platform that can process more than a million I/O requests in a second (1MIOPS) while hiding long latencies imposed by its internal flash media. Inspired by a parallel data analysis system, we design the firmware based on many-to-many threading model that can be scaled horizontally. The proposed DeepFlash can extract the maximum performance of the underlying flash memory complex by concurrently executing multiple firmware components across many cores within the device. To show its extreme parallel scalability, we implement DeepFlash on a many-core prototype processor that employs dozens of lightweight cores, analyze new challenges from parallel I/O processing and address the challenges by applying concurrency-aware optimizations. Our comprehensive evaluation reveals that DeepFlash can serve around 4.5 GB/s, while minimizing the CPU demand on microbenchmarks and real server workloads.

[Paper download](https://www.usenix.org/system/files/fast20-zhang_jie.pdf)

Recommended citation: Zhang, Jie, Miryeong Kwon, Michael Swift, and Myoungsoo Jung. "Scalable Parallel Flash Firmware for Many-core Architectures." In 18th {USENIX} Conference on File and Storage Technologies ({FAST} 20), pp. 121-136. 2020.