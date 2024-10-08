---
title: "Achieving Near-Zero Read Retry for 3D NAND Flash Memory"
collection: publications
permalink: /publication/2024-readretry
excerpt: 'We characterize different types of real flash chips, based on which we further develop models for the correlation among the optimal read offsets of read voltages required for reading each page. By leveraging characterization observations and the models, we propose a methodology to generate a tailored RRT for each flash model…'
date: 2024-06-01
venue: 'ACM Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
As the flash-based storage devices age with program/erase (P/E) cycles, they require an increasing number of read retries for error correction, which in turn deteriorates their read performance. The design of read-retry methods is critical to flash read performance. Current flash chips embed predefined read retry tables (RRT) for retry, but these tables fail to consider the read granularity and error behaviors. We characterize different types of real flash chips, based on which we further develop models for the correlation among the optimal read offsets of read voltages required for reading each page. By leveraging characterization observations and the models, we propose a methodology to generate a tailored RRT for each flash model. We introduce a dynamic read retry procedure to pick up proper read voltages from the table, followed by a proximity-search method for fine-tuning the read offsets. Experiments on real flash chips show that the proposed methodology can achieve near-zero retries. It reduces the average number of read retries to below 0.003 for data with high retention time at 8K P/E cycles, whereas the state-of-the-art approaches incur over 3 read retries on average once the flash is aged to 3K P/E cycles.

[Paper download](https://doi.org/10.1145/3620665.3640372)

Recommended citation: Ye, Min, Qiao Li, Yina Lv, Jie Zhang, Tianyu Ren, Daniel Wen, Tei-Wei Kuo, and Chun Jason Xue. "Achieving Near-Zero Read Retry for 3D NAND Flash Memory." In Proceedings of the 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2, pp. 55-70. 2024.