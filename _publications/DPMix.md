---
title: "DP-Mix: Differentially Private Routing in Mix Networks"
collection: publications
category: conferences
permalink: /publication/DPMix.md
excerpt: 'Mixnets, as overlay networks, ensure anonymity for
messages by forwarding them through intermediary nodes that
obscure their traffic patterns from network-level adversaries.
Nonetheless, the selection of intermediaries is traditionally
performed uniformly at random, resulting in optimal routes
being chosen no more frequently than suboptimal ones. This
often causes messages to traverse inefficient paths that degrade
performance or weaken security. While there have been proposals to improve route selection in mixnets, they are limited
to latency reduction and rely on heuristic strategies that lack
formal anonymity guarantees.
To bridge this gap, we develop a framework for differentially private routing in mixnets aimed at general-purpose
optimization. In this framework, each candidate route is assigned an optimality score, and routes are then selected to
favor high-scoring paths while preserving anonymity under
a pure differential privacy guarantee. We instantiate this
model for optimizing path security, enhancing reliability, and
minimizing communication latency. Additionally, we introduce
a gradient-based algorithm applied post hoc to the route
selection process—without weakening privacy guarantees—to
prevent the over-selection of particular nodes, which could
otherwise lead to security vulnerabilities or network congestion.'
date: 2025-12-20
venue: 'Annual Computer Security Applications Conference (ACSAC)'
slidesurl: 'http://mmaahhddii1995.github.io/files/DP_Mix_slides.pdf'
paperurl: 'http://mmaahhddii1995.github.io/files/DP_Mix_paper.pdf'
bibtexurl: 'http://mmaahhddii1995.github.io/files/DP_Mix_bib.bib'
artifacturl:'https://github.com/DPMix/'
videourl:'https://youtu.be/K4gEQw0qYNw'
citation: 'M. Rahimi, “DP-Mix: Differentially Private Routing in Mix Networks,” to appear in ACSAC 2025: 41st Annual Computer Security Applications Conference, IEEE.  '
---
The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
