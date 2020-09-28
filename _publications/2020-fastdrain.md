---
title: "FastDrain: Removing Page Victimization Overheads in NVMe Storage Stack"
collection: publications
permalink: /publication/2020-fastdrain
excerpt: 'Host-side page victimizations can easily overflow the SSD internal buffer, which interferes I/O services of diverse user applications thereby degrading user-level experiences. To address this, we propose FastDrain, a co-design of OS kernel and flash firmware to avoid the buffer overflow, caused by page victimizations. Specifically, FastDrain can detect a triggering point where a near-future page victimization introduces an overflow of the SSD internal buffer…'
date: 2020-04-01
venue: 'Computer Architecture Letters'
#paperurl: ''
#citation: 'Zhang, Jie, Miryeong Kwon, Sanghyun Han, Nam Sung Kim, Mahmut Kandemir, and Myoungsoo Jung. "FastDrain: Removing Page Victimization Overheads in NVMe Storage Stack." IEEE Computer Architecture Letters 19, no. 2 (2020): 92-96.'
---
Host-side page victimizations can easily overflow the SSD internal buffer, which interferes I/O services of diverse user applications thereby degrading user-level experiences. To address this, we propose FastDrain, a co-design of OS kernel and flash firmware to avoid the buffer overflow, caused by page victimizations. Specifically, FastDrain can detect a triggering point where a near-future page victimization introduces an overflow of the SSD internal buffer. Our new flash firmware then speculatively scrubs the buffer space to accommodate the requests caused by the page victimization. In parallel, our new OS kernel design controls the traffic of page victimizations by considering the target device buffer status, which can further reduce the risk of buffer overflow. To secure more buffer spaces, we also design a latency-aware FTL, which dumps the dirty data only to the fast flash pages. Our evaluation results reveal that FastDrain reduces the 99th response time of user applications by 84%, compared to a conventional system.

[Download paper here](https://arxiv.org/abs/2006.08966)

Recommended citation: Zhang, Jie, Miryeong Kwon, Sanghyun Han, Nam Sung Kim, Mahmut Kandemir, and Myoungsoo Jung. "FastDrain: Removing Page Victimization Overheads in NVMe Storage Stack." IEEE Computer Architecture Letters 19, no. 2 (2020): 92-96.