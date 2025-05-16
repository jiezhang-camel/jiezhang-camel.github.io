---
title: "ArtMem: Adaptive Migration in Reinforcement Learning-Enabled Tiered Memory"
collection: publications
permalink: /publication/2025-artmem
excerpt: 'This paper proposes ArtMem, a reinforcement learning (RL)-driven framework that dynamically manages tiered memory systems and adapts to workload evolution. ArtMem incorporates system-level feedback, such as access frequency, recency, and migration counts, for adaptive page migrations. ArtMem enables better placement of memory pages, enhancing system performance while reducing unnecessary migrations…'
date: 2025-06-01
venue: 'IEEE/ACM International Symposium on Computer Architecture (ISCA)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
With the increasing memory demands of emerging applications, tiered memory has become a viable solution for reducing data center hardware costs. Given the low performance of the capacity tiers in tiered memory systems, optimizing memory management is crucial in improving overall system performance. This paper identifies three key limitations in existing tiered memory solutions. First, they often perform inconsistently across different workloads, leading to suboptimal performance in some workloads. Second, they often fail to adjust migration strategies in response to low fast memory tier access rates, resulting in ineffective data placement. Third, they missed the opportunity to dynamically tune the memory migration scope based on workload patterns, leading to unnecessary page migrations and underutilization of tiered memory potential. To address these issues, this paper proposes ArtMem, a reinforcement learning (RL)-driven framework that dynamically manages tiered memory systems and adapts to workload evolution. ArtMem incorporates system-level feedback, such as access frequency, recency, and migration counts, for adaptive page migrations. ArtMem enables better placement of memory pages, enhancing system performance while reducing unnecessary migrations. Experimental evaluations show that ArtMem outperforms state-of-the-art tiering systems, achieving performance improvements ranging from 35% to 191%, over diverse workloads.

[Paper download](N/A)

Recommended citation: N/A.