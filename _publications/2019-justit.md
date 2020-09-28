---
title: "Maximizing GPU Cache Utilization with Adjustable Cache Line Management"
collection: publications
permalink: /publication/2019-justit
excerpt: 'Executing the irregular applications in general-purpose graphics processing units (GPGPUs) exposes serious challenges to their cache system. This paper proposes JUSTIT, an adjustable cache line management design that maximizes the GPU L1D cache utilization by being aware of the memory request access granularity…'
date: 2019-06-01
venue: 'Korea Computer Congress (KCC)'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Executing the irregular applications in general-purpose graphics processing units (GPGPUs) exposes serious challenges to their cache system. This paper proposes JUSTIT, an adjustable cache line management design that maximizes the GPU L1D cache utilization by being aware of the memory request access granularity. Specifically, JUSTIT can identify the 1-sector memory requests with a singular access and directly bypass L1D cache to prevent these memory requests from polluting the limited L1D cache space. For the other 1-sector memory requests, we redirect them to shared memory for future accesses. Our evaluation reveals that JUSTIT improves the IPC by 28%, compared to a state of the art memory management system.

[Paper download](ttps://github.com/jiezhang-camel/jiezhang-camel.github.io/blob/master/files/CacheBypass.pdf)

Recommended citation: Zhang, Jie, and Myoungsoo Jung. "Maximizing GPU Cache Utilization with Adjustable Cache Line Management." In 2019 Korea Computer Congress (KCC), 2019.