---
title: "When Mixnets Fail: Evaluating, Quantifying, and Mitigating the Impact of Adversarial Nodes in Mix Networks"
collection: publications
category: conferences
permalink: /publication/WhenMixnetsFail.md
excerpt: 'Mix networks (mixnets) provide clients with communication anonymity against strong network adversaries by traversing their packets independently through randomly selected hops (mixnodes), which disrupt packet linkability. Although this approach, implemented in Nym, maximizes obfuscation against network adversaries, it enables an adversary who compromises a subset of mixnodes (10%/5% of nodes) to entirely nullify the anonymity of all clients whose communication volume with their destination exceeds a certain threshold ($4$MB/$30$MB).
To mitigate such vulnerabilities, this work develops a set of novel path selection techniques that achieve a trade-off between resistance to network adversaries and resilience against compromised mixnodes. Observing that existing anonymity metrics are insufficient to quantify adversarial risk in mixnets, we additionally introduce effective empirical and simulation-based metrics.
Through theoretical, empirical, and simulation-based evaluations, we comprehensively assess our proposals, demonstrating that the proposed approaches reduce the vulnerability to compromised nodes by up to 80%, while conferring limited advantage to network adversaries. Our analysis further reveals that state-of-the-art anonymity metrics, in contrast to our proposed metrics, produce misleading results that influenced certain design choices in Nym.'
date: 2026-2-27
venue: 'Network and Distributed System Security (NDSS) Symposium'
paperurl: 'http://mmaahhddii1995.github.io/files/WhenMixnetsFail.pdf'
bibtexurl: 'http://mmaahhddii1995.github.io/files/WhenMixnetsFail_bib.bib'
artifacturl: 'https://github.com/whenmixnetsfail/mix_adversary/'
citation: 'M. Rahimi "When Mixnets Fail: Evaluating, Quantifying, and Mitigating the Impact of Adversarial Nodes in Mix Networks," in NDSS 2026: 33rd Symposium on Network and Distributed System Security, Internet Society.'
---
The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
