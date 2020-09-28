---
title: "DUANG: Fast and Lightweight Page Migration in Asymmetric Memory Systems"
collection: publications
permalink: /publication/2016-duang
excerpt: 'In this paper, we propose a novel resistive memory architecture sharing a set of row buffers between a pair of neighboring banks. It enables two attractive techniques: (1) migrating memory pages between slow and fast banks with little performance overhead and (2) adaptively allocating more row buffers to busier banks based on memory access patterns…'
date: 2016-02-01
venue: 'IEEE Symposium on High Performance Computer Architecture (HPCA)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Main memory systems have gone through dramatic increases in bandwidth and capacity. At the same time, their random access latency has remained relatively constant. For given memory technology, optimizing the latency typically requires sacrificing the density (i.e., cost per bit), which is one of the most critical concerns for memory industry. Recent studies have proposed memory architectures comprised of asymmetric (fast/low-density and slow/high-density) regions to optimize between overall latency and negative impact on density. Such memory architectures attempt to cost-effectively offer both high capacity and high performance. Yet they present a unique challenge, requiring direct placements of hot memory pages 1 in the fast region and/or expensive runtime page migrations. In this paper, we propose a novel resistive memory architecture sharing a set of row buffers between a pair of neighboring banks. It enables two attractive techniques: (1) migrating memory pages between slow and fast banks with little performance overhead and (2) adaptively allocating more row buffers to busier banks based on memory access patterns. For an asymmetric memory architecture with both slow/high-density and fast/low-density banks, our shared row-buffer architecture can capture 87-93% of the performance of a memory architecture with only fast banks.

[Paper download](http://camelab.org/uploads/Main/duang.pdf)

Recommended citation: Wang, Hao, Jie Zhang, Sharmila Shridhar, Gieseo Park, Myoungsoo Jung, and Nam Sung Kim. "DUANG: Fast and lightweight page migration in asymmetric memory systems." In 2016 IEEE International Symposium on High Performance Computer Architecture (HPCA), pp. 481-493. IEEE, 2016.