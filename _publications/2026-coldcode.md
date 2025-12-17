---
title: "ColdCode: Cold Data Encoding for Enhanced Reliability and Lifetime in 3D NAND Flash"
collection: publications
permalink: /publication/2026-coldcode
excerpt: 'Cold storage, which stores rarely accessed data, dominates modern data centers but is poorly served by NAND flash data randomization. As a common practice today by flash vendors, data randomization is applied in NAND flash chips to avoid extreme data patterns that generate the worst-case raw bit error rate (RBER). However, this paper demonstrates that data randomization rules out the opportunity to explore data patterns with very low RBERs…'
date: 2026-04-27
venue: 'European Conference on Computer Systems (Eurosys)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Cold storage, which stores rarely accessed data, dominates modern data centers but is poorly served by NAND flash's data randomization. As a common practice today by flash vendors, data randomization is applied in NAND flash chips to avoid extreme data patterns that generate the worst-case raw bit error rate (RBER). However, this paper demonstrates that data randomization rules out the opportunity to explore data patterns with very low RBERs, through a comprehensive analysis on data randomization in 3D NAND flash chips (across 8 models). Motivated by this, we propose ColdCode, a novel data coding framework to replace the conventional randomizer in 3D high-density flash for cold data storage. Using a tag that indicates coldness information passed from the file system to solid-state drive (SSD) controllers, the controller encodes cold data to enhance reliability and extend lifetime. ColdCode employs two coding techniques: skewed coding and reversed Huffman coding, applied based on the data entropy. These techniques effectively reduce the RBER of encoded data compared to conventional randomization. Experimental results on real high-density 3D flash chips show that, under the same error conditions, the skewed coding and reversed Huffman coding reduce the average RBER by 42% and 30%, respectively. Consequently, the lifetime of the flash chips is prolonged by factors of 2.8× and 1.7×, respectively, compared to data randomization.

[Paper download](N/A)

Recommended citation: N/A.