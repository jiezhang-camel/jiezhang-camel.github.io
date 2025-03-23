---
title: "Daredevil: Rescue Your Flash Storage from Inflexible Kernel Storage Stack"
collection: publications
permalink: /publication/2025-daredevil
excerpt: 'We propose Daredevil, a novel kernel storage stack, which addresses this issue by decoupling the static bindings and allowing full connectivity between cores and NQs. Therefore, it grants multi-tenancy control the flexibility to freely route requests among NQs according to their SLAs. Moreover, it incorporates multi-tenancy-aware scheduling on NQs to facilitate efficient request routing…'
date: 2025-04-01
venue: 'ACM European Conference on Computer Systems (Eurosys)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Existing kernel storage stacks struggle to mitigate the multi-tenancy issue for NVMe SSDs, due to performance interference between I/O requests from tenants with different SLAs. Addressing this requires separating their I/O requests within the NVMe I/O queues (NQs). However, our analysis reveals that the static CPU core-NQ bindings of current storage stacks restrict their flexibility to achieve this goal.

We propose Daredevil, a novel kernel storage stack, which addresses this issue by decoupling the static bindings and allowing full connectivity between cores and NQs. Therefore, it grants multi-tenancy control the flexibility to freely route requests among NQs according to their SLAs. Moreover, it incorporates multi-tenancy-aware scheduling on NQs to facilitate efficient request routing. Our evaluation shows that Daredevil can reduce I/O request latency by up to 3-170× compared to current kernel storage stacks, while maintaining comparable throughput.

[Paper download](N/A)

Recommended citation: N/A.