---
title: "ReveNAND: A Fast-Drift Aware Resilient 3D NAND Flash Design"
collection: publications
permalink: /publication/2018-revenand
excerpt: 'In this work, we first present an elastic read reference (VRef) scheme (ERR) for reducing such errors in ReveNAND—our fast-drift aware 3D NAND design. To address the inherent limitation of the adaptive VRef, we introduce a new intra-block page organization (hitch-hike) that can enable stronger error correction for the error-prone pages. In addition, we propose a novel reinforcement-learning-based smart data refill scheme (iRefill) to counter the impact of fast-drift with minimum performance and hardware overhead. Finally, we present the first analytic model to characterize fast-drift and evaluate its system-level impact....'
date: 2018-03-01
venue: 'ACM Transactions on Architecture and Code Optimization (TACO)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
The paradigm shift from planar (two dimensional (2D)) to vertical (three-dimensional (3D)) models has placed the NAND flash technology on the verge of a design evolution that can handle the demands of next-generation storage applications. However, it also introduces challenges that may obstruct the realization of such 3D NAND flash. Specifically, we observed that the fast threshold drift (fast-drift) in a charge-trap flash-based 3D NAND cell can make it lose a critical fraction of the stored charge relatively soon after programming and generate errors.

In this work, we first present an elastic read reference (VRef) scheme (ERR) for reducing such errors in ReveNAND—our fast-drift aware 3D NAND design. To address the inherent limitation of the adaptive VRef, we introduce a new intra-block page organization (hitch-hike) that can enable stronger error correction for the error-prone pages. In addition, we propose a novel reinforcement-learning-based smart data refill scheme (iRefill) to counter the impact of fast-drift with minimum performance and hardware overhead. Finally, we present the first analytic model to characterize fast-drift and evaluate its system-level impact. Our results show that, compared to conventional 3D NAND design, our ReveNAND can reduce fast-drift errors by 87%, on average, and can lower the ECC latency and energy overheads by 13× and 10×, respectively.

[Download paper here](https://dl.acm.org/doi/10.1145/3184744)

Recommended citation: Shihab, Mustafa M., Jie Zhang, Myoungsoo Jung, and Mahmut Kandemir. "ReveNAND: A fast-drift-aware resilient 3D NAND flash design." ACM Transactions on Architecture and Code Optimization (TACO) 15, no. 2 (2018): 1-26.