---
title: "XHarvest: Rethinking High-Performance and Cost-Efficient SSD Architecture with CXL-Driven Harvesting"
collection: publications
permalink: /publication/2024-flagger
excerpt: 'We propose XHarvest, a new cost-efficient and high-performance SSD architecture, which harnesses compute express link (CXL) and trusted execution environment (TEE) to facilitate dynamic, efficient, and secure host resource harvesting. It reserves moderate SSD internal resources to isolate SSD internal tasks and applications under regular I/O loads while coping with occasional I/O bursts via host resource harvesting…'
date: 2025-06-01
venue: 'IEEE/ACM International Symposium on Computer Architecture (ISCA)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
The occasional nature of I/O bursts in production clusters makes the substantial and expensive SSD internal resources always underutilized, resulting in cost inefficiency. Open-Channel SSD (OCSSD), as a pioneering solution, removes the SSD internal resources but rather leverages the host-side resources to serve I/O requests. Unfortunately, it faces adoption obstacles due to the heavy resource contention with user applications, hampered host-SSD collaboration, and proprietary firmware leakage risks. Tackling these challenges, we propose XHarvest, a new cost-efficient and high-performance SSD architecture, which harnesses compute express link (CXL) and trusted execution environment (TEE) to facilitate dynamic, efficient, and secure host resource harvesting. It reserves moderate SSD internal resources to isolate SSD internal tasks and applications under regular I/O loads while coping with occasional I/O bursts via host resource harvesting. To this end, it executes the firmware within the host-side TEE without disclosing sensitive algorithms while leveraging the cache-coherent and fine-grained CXL to build a unified and efficient metadata cache. XHarvest also capitalizes on the CXL and its security feature to enable secure and efficient host-SSD collaboration. The evaluation results show that XHarvest reduces the hardware cost by 31.50% while achieving the same or even higher performance than conventional SSDs.

[Paper download](N/A)

Recommended citation: N/A.