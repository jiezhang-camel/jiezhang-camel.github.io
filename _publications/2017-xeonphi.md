---
title: "An In-depth Performance Analysis of Many-Integrated Core for Communication Efficient Heterogeneous Computing"
collection: publications
permalink: /publication/2017-xeonphi
excerpt: 'Many-integrated core (MIC) architecture combines dozens of reduced x86 cores onto a single chip to offer high degrees of parallelism. The parallel user applications executed across many cores that exist in one or more MICs require a series of work related to data sharing and synchronization with the host. In this work, we build a real CPU+MIC heterogeneous cluster and analyze its performance behaviors by examining different communication methods such as message passing method and remote direct memory accesses…'
date: 2017-10-01
venue: 'IFIP International Conference on Network and Parallel Computing (NPC)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Many-integrated core (MIC) architecture combines dozens of reduced x86 cores onto a single chip to offer high degrees of parallelism. The parallel user applications executed across many cores that exist in one or more MICs require a series of work related to data sharing and synchronization with the host. In this work, we build a real CPU+MIC heterogeneous cluster and analyze its performance behaviors by examining different communication methods such as message passing method and remote direct memory accesses. Our evaluation results and in-depth studies reveal that (i) aggregating small messages can improve network bandwidth without violating latency restrictions, (ii) while MICs can execute hundreds of hardware cores, the highest network throughput is achieved when only 4   ∼  6 point-to-point connections are established for data communication, (iii) data communication over multiple point-to-point connections between host and MICs introduce severe load unbalancing, which require to be optimized for future heterogeneous computing.

[Paper download](https://link.springer.com/chapter/10.1007/978-3-319-68210-5_19)

Recommended citation: Zhang, Jie, and Myoungsoo Jung. "An in-depth performance analysis of many-integrated core for communication efficient heterogeneous computing." In IFIP International Conference on Network and Parallel Computing, pp. 155-159. Springer, Cham, 2017.