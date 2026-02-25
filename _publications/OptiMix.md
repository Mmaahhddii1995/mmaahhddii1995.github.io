---
title: "OptiMix: Scalable and Distributed Approaches for Latency Optimization in Modern Mixnets"
collection: publications
category: conferences
permalink: /publication/OptiMix.md
excerpt: 'Mixnets provide network-level anonymity, traded off with increased communication latency, which consequently limits their applicability to only latency-tolerant applications, shrinking the anonymity set to clients engaged in such use cases. Addressing this issue requires optimizing latency, as recently explored in LARMix (NDSS’24) and LAMP (NDSS’25) through node arrangement and strategic routing. However, these approaches are tailored to specific mixnet designs, rely on simplified models and trust assumptions, or suffer from limited practical efficiency.
In contrast, OptiMix bridges these gaps by introducing a general low-latency mixnet model adaptable to all well-established designs. To this end, we first propose an efficient distributed protocol for arranging nodes in mixnets that achieves low-latency properties while maintaining unbiasability against adversaries.
Second, we introduce novel strategic routing schemes that optimize communication latency. Third, we design a load-balancing algorithm that evenly distributes traffic without undermining the latency-optimized characteristics of the routing strategies. Fourth, we conduct extensive evaluations using data from the deployed Nym mixnet, demonstrating substantial latency reductions with minimal anonymity loss across various mixnet designs—achieving up to 4x performance gains over state-of-the-art solutions.
Finally, considering that latency reduction incurs either anonymity degradation or increased bandwidth overhead—as stated by the anonymity trilemma—we propose a cover-routing mechanism that enables clients to benefit from low-latency mixnets without compromising anonymity, at the modest cost of generating additional cover traffic.'
date: 2025-2-27
venue: 'Network and Distributed System Security (NDSS) Symposium'
paperurl: 'http://mmaahhddii1995.github.io/files/OptiMix.pdf'
bibtexurl: 'http://mmaahhddii1995.github.io/files/OptiMix_bib.bib'
artifacturl: 'https://github.com/OptiMixnet/OptiMix'
citation: 'M. Rahimi "OptiMix: Scalable and Distributed Approaches for Latency Optimization in Modern Mixnets," in NDSS 2026: 33rd Symposium on Network and Distributed System Security, Internet Society.'
---
The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
