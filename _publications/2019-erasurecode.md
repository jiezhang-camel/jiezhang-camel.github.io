---
title: "Exploring Fault-Tolerant Erasure Codes for Scalable All-Flash Array Clusters"
collection: publications
permalink: /publication/2019-erasurecode
excerpt: 'To understand the impact of using erasure coding on the system performance and other system aspects such as CPU utilization and network traffic, we build a storage cluster that consists of approximately 100 processor cores with more than 50 high-performance solid-state drives (SSDs), and evaluate the cluster with a popular open-source distributed parallel file system, called Ceph…'
date: 2019-08-01
venue: 'IEEE Transactions on Parallel and Distributed Systems (TPDS)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Large-scale systems with all-flash arrays have become increasingly common in many computing segments. To make such systems resilient, we can adopt erasure coding such as Reed-Solomon (RS) code as an alternative to replication because erasure coding incurs a significantly lower storage overhead than replication. To understand the impact of using erasure coding on the system performance and other system aspects such as CPU utilization and network traffic, we build a storage cluster that consists of approximately 100 processor cores with more than 50 high-performance solid-state drives (SSDs), and evaluate the cluster with a popular open-source distributed parallel file system, called Ceph. Specifically, we analyze the behaviors of a system adopting erasure coding from the following five viewpoints, and compare with those of another system using replication: (1) storage system I/O performance; (2) computing and software overheads; (3) I/O amplification; (4) network traffic among storage nodes, and (5) impact of physical data layout on performance of RS-coded SSD arrays. For all these analyses, we examine two representative RS configurations, used by Google file systems, and compare them with triple replication employed by a typical parallel file system as a default fault tolerance mechanism. Lastly, we collect 96 block-level traces from the cluster and release them to the public domain for the use of other researchers.

[Download paper here](https://arxiv.org/pdf/1906.08602.pdf)

Recommended citation: Koh, Sungjoon, Jie Zhang, Miryeong Kwon, Jungyeon Yoon, David Donofrio, Nam Sung Kim, and Myoungsoo Jung. "Exploring fault-tolerant erasure codes for scalable all-flash array clusters." IEEE Transactions on Parallel and Distributed Systems 30, no. 6 (2018): 1312-1330.