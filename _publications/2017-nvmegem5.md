---
title: "Enabling Realistic Logical Device Interface and Driver for NVM Express Enabled Full System Simulations"
collection: publications
permalink: /publication/2017-nvmegem5
excerpt: 'In this work, we implement an NVMe disk and controller to enable a realistic storage stack of next generation interfaces and integrate them into gem5 and a high-fidelity solid state disk simulation model. We verify the functionalities of NVMe that we implemented, using a standard user-level tool, called NVMe command line interface…'
date: 2017-10-01
venue: 'IFIP International Conference on Network and Parallel Computing (NPC) and Invited for International Journal of Parallel Programming (IJPP)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Data volumes are drastically increasing, immense information created over the past 10 years exceeds the storage capacity across all media types. While the storage systems play a critical role in modern memory hierarchy, their interfaces and simulation models are overly simplified by computer-system architecture research. Specifically, gem5, a popular full system simulator, includes only Integrated Drive Electronics interface, which was originally designed three decades ago, and simulates the underlying storage device with a constant latency value. In this work, we implement an NVMe disk and controller to enable a realistic storage stack of next generation interfaces and integrate them into gem5 and a high-fidelity solid state disk simulation model. We verify the functionalities of NVMe that we implemented, using a standard user-level tool, called NVMe command line interface. Our evaluation results reveal that the performance of a high performance SSD can significantly vary based on different software stacks and storage controllers even under the same condition of device configurations and degrees of parallelism. Specifically, the traditional interface caps the performance of the SSD by 95%, whereas NVMe interface we implement in gem5 can successfully reveal the true performance aggregated by many underlying flash-based media.

[Paper download](https://link.springer.com/article/10.1007/s10766-017-0530-1)

Recommended citation: Gouk, Donghyun, Jie Zhang, and Myoungsoo Jung. "Enabling realistic logical device interface and driver for nvm express enabled full system simulations." International Journal of Parallel Programming 46, no. 4 (2018): 710-721.