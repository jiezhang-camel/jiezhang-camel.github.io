---
title: "StreamPIM: Streaming Matrix Computation in Racetrack Memory"
collection: publications
permalink: /publication/2024-streampim
excerpt: 'We propose StreamPIM, a new processing-in-RM architecture, which tightly couples the memory core and the computation units. Specifically, StreamPIM directly constructs a matrix processor from domain-wall nanowires without the usage of CMOS-based computation units. It also designs a domainwall nanowire-based bus, which can eliminate electromagnetic conversion…'
date: 2024-03-01
venue: 'IEEE International Symposium on High-Performance Computer Architecture (HPCA)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Racetrack memory (RM) techniques have become promising solutions to resolve the memory wall issue as they increase memory density, reduce energy consumption and are capable of building processing-in-memory (PIM) architectures. RM can place arithmetic logic units in or near its memory arrays to process tasks offloaded by the host. While there already exist multiple studies of processing in RM, these solutions, unfortunately, suffer from data transfer overheads imposed by the loose coupling of the memory core and the computation units. To address this issue, we propose StreamPIM, a new processing-in-RM architecture, which tightly couples the memory core and the computation units. Specifically, StreamPIM directly constructs a matrix processor from domain-wall nanowires without the usage of CMOS-based computation units. It also designs a domainwall nanowire-based bus, which can eliminate electromagnetic conversion. StreamPIM further optimizes the performance by leveraging RM internal parallelism. Our evaluation results show that StreamPIM achieves 39.1× higher performance and saves 58.4× energy consumption, compared with the traditional computing platform.

[Paper download](https://ieeexplore.ieee.org/abstract/document/10476415)

Recommended citation: An, Yuda, Yunxiao Tang, Shushu Yi, Li Peng, Xiurui Pan, Guangyu Sun, Zhaochu Luo, Qiao Li, and Jie Zhang. "StreamPIM: Streaming Matrix Computation in Racetrack Memory." In 2024 IEEE International Symposium on High-Performance Computer Architecture (HPCA), pp. 297-311. IEEE, 2024.