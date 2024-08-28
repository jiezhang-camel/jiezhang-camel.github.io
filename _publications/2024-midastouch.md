---
title: "Midas Touch: Invalid-Data Assisted Reliability and Performance Boost for 3D High-Density Flash"
collection: publications
permalink: /publication/2024-midastouch
excerpt: 'This work proposes invalid-data assisted strategies for performance and reliability boosting of valid data in 3D QLC-based flash storage systems. We first propose a high-efficiency re-programming (RP) scheme to reprogram the valid data and a high-reliability not-programming (NP) scheme to program data on the partially-invalid WLs…'
date: 2024-03-01
venue: 'IEEE International Symposium on High-Performance Computer Architecture (HPCA)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
High-density 3D NAND flash like QLC (Quad-Level Cell) is prevailing in providing large capacities for data-intensive applications. Because of the structure limitation, a two-step programming with a specific sequence is adopted in 3D QLC flash, where data could become invalid between the two programming steps. This is called invalid programming, as the second-step programming is conducted on partially-invalid wordlines (WLs). By exploiting this phenomenon, this work proposes invalid-data assisted strategies for performance and reliability boosting of valid data in 3D QLC-based flash storage systems. We first propose a high-efficiency re-programming (RP) scheme to reprogram the valid data and a high-reliability not-programming (NP) scheme to program data on the partially-invalid WLs. An adaptive data allocation (ADA) strategy for data management between the SLC and QLC regions is further introduced to reduce the occurrence of invalid programming. The simulatorbased experiments show the proposed RP scheme combined with ADA can reduce the execution time for programming by 13.51%, on average. Through real-device evaluations, we present that the NP scheme can reduce the bit error rate of NP-programmed data by 32.8% of the worst page type, thus improving overall reliability, which translates to 12% reduction in refreshing overheads and 30% lifetime extension, on average. Besides, the NP scheme with ADA averagely reduces energy consumption by 4.8%.

[Paper download](https://ieeexplore.ieee.org/abstract/document/10476428)

Recommended citation: Li, Qiao, Hongyang Dang, Zheng Wan, Congming Gao, Min Ye, Jie Zhang, Tei-Wei Kuo, and Chun Jason Xue. "Midas Touch: Invalid-Data Assisted Reliability and Performance Boost for 3d High-Density Flash." In 2024 IEEE International Symposium on High-Performance Computer Architecture (HPCA), pp. 657-670. IEEE, 2024.