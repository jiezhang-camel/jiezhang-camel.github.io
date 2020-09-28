---
title: "Faster than Flash: An In-Depth Study of System Challenges for Emerging Ultra-Low Latency SSDs"
collection: publications
permalink: /publication/2019-fastssd
excerpt: 'In this work, we comprehensively perform empirical evaluations with 800GB ULL SSD prototypes and characterize ULL behaviors by considering a wide range of I/O path parameters, such as different queues and access patterns. We then analyze the efficiencies and challenges of the polled-mode and hybrid polling I/O completion methods (added into Linux kernels 4.4 and 4.10, respectively) and compare them with the efficiencies of a conventional interrupt-based I/O path…'
date: 2019-10-01
venue: 'IEEE International Symposium on Workload Characterization (IISWC)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Emerging storage systems with new flash exhibit ultra-low latency (ULL) that can address performance disparities between DRAM and conventional solid state drives (SSDs) in the memory hierarchy. Considering the advanced low-latency characteristics, different types of I/O completion methods (polling/hybrid) and storage stack architecture (SPDK) are proposed. While these new techniques are expected to take costly software interventions off the critical path in ULL-applied systems, unfortunately no study exists to quantitatively analyze system-level characteristics and challenges of combining such newly-introduced techniques with real ULL SSDs. In this work, we comprehensively perform empirical evaluations with 800GB ULL SSD prototypes and characterize ULL behaviors by considering a wide range of I/O path parameters, such as different queues and access patterns. We then analyze the efficiencies and challenges of the polled-mode and hybrid polling I/O completion methods (added into Linux kernels 4.4 and 4.10, respectively) and compare them with the efficiencies of a conventional interrupt-based I/O path. In addition, we revisit the common expectations of SPDK by examining all the system resources and parameters. Finally, we demonstrate the challenges of ULL SSDs in a real SPDK-enabled server-client system. Based on the performance behaviors that this study uncovers, we also discuss several system implications, which are required to take a full advantage of ULL SSD in the future.

[Download paper here](https://arxiv.org/pdf/1912.06998.pdf)

Recommended citation: Koh, Sungjoon, Junhyeok Jang, Changrim Lee, Miryeong Kwon, Jie Zhang, and Myoungsoo Jung. "Faster than flash: An in-depth study of system challenges for emerging ultra-low latency ssds." In 2019 IEEE International Symposium on Workload Characterization (IISWC), pp. 216-227. IEEE, 2019.