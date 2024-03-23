---
title: "LearnedFTL: A Learning-based Page-level FTL for Reducing Double Reads in Flash-based SSDs"
collection: publications
permalink: /publication/2024-learnedftl
excerpt: 'We present LearnedFTL, a new on-demand pagelevel flash translation layer (FTL) design, which employs learned indexes to improve the address translation efficiency of flashbased SSDs. The first of its kind, it reduces the number of double reads induced by address translation in random read accesses. LearnedFTL proposes three key techniques…'
date: 2024-03-01
venue: 'IEEE International Symposium on High-Performance Computer Architecture (HPCA)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
We present LearnedFTL, a new on-demand pagelevel flash translation layer (FTL) design, which employs learned indexes to improve the address translation efficiency of flashbased SSDs. The first of its kind, it reduces the number of double reads induced by address translation in random read accesses. LearnedFTL proposes three key techniques: an in-place-update linear model to build learned indexes efficiently, a virtual PPN representation to obtain contiguous PPNs for sorted LPNs, and a group-based allocation and model training via GC/rewrite strategy to reduce the training overhead. By tightly integrating the aforementioned key techniques, LearnedFTL considerably speeds up address translation while reducing the number of flash read accesses caused by the address translation. Our extensive experiments on a FEMU-based prototype show that LearnedFTL can reduce up to 55.5% address translation-induced double reads. As a result, LearnedFTL reduces the P99 tail latency by 2.9× ∼ 12.2× with an average of 5.5× and 8.2× compared to the state-of-the-art TPFTL and LeaFTL schemes, respectively.

[Paper download](N/A)

Recommended citation:.