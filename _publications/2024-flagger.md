---
title: "Flagger: Cooperative Acceleration for Large-Scale Cross-Silo Federated Learning Aggregation"
collection: publications
permalink: /publication/2024-flagger
excerpt: 'We propose Flagger, an efficient and high-performance FL aggregator. Flagger meticulously integrates the data processing unit (DPU) with computational storage drives (CSD), employing these two distinct near-data processing (NDP) accelerators as a holistic architecture to collaboratively enhance FL aggregation…'
date: 2024-06-29
venue: 'IEEE/ACM International Symposium on Computer Architecture (ISCA)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Cross-silo federated learning (FL) leverages homomorphic encryption (HE) to obscure the model updates from the clients. However, HE poses the challenges of complex cryptographic computations and inflated ciphertext sizes. As cross-silo FL scales to accommodate larger models and more clients, the overheads of HE can overwhelm a CPU-centric aggregator architecture, including excessive network traffic, enormous data volume, intricate computations, and redundant data movements. Tackling these issues, we propose Flagger, an efficient and high-performance FL aggregator. Flagger meticulously integrates the data processing unit (DPU) with computational storage drives (CSD), employing these two distinct near-data processing (NDP) accelerators as a holistic architecture to collaboratively enhance FL aggregation. With the delicate delegation of complex FL aggregation tasks, we build Flagger-DPU and Flagger-CSD to exploit both in-network and in-storage HE acceleration to streamline FL aggregation. We also implement Flagger-Runtime, a dedicated software layer, to coordinate NDP accelerators and enable direct peer-to-peer data exchanges, markedly reducing data migration burdens. Our evaluation results reveal that Flagger expedites the aggregation in FL training iterations by 436% on average, compared with traditional CPU-centric aggregators.

[Paper download](https://ieeexplore.ieee.org/abstract/document/10609633)

Recommended citation: Pan, Xiurui, Yuda An, Shengwen Liang, Bo Mao, Mingzhe Zhang, Qiao Li, Myoungsoo Jung, and Jie Zhang. "Flagger: Cooperative Acceleration for Large-Scale Cross-Silo Federated Learning Aggregation." In 2024 ACM/IEEE 51st Annual International Symposium on Computer Architecture (ISCA), pp. 915-930. IEEE, 2024.