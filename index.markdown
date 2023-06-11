---
layout: home
title: Massively Scalable Inverse Reinforcement Learning in Google Maps
author:
- {name: Matt Barnes, affiliation: 1}
- {name: Matthew Abueg, affiliation: 1}
- {name: Oliver F. Lange, affiliation: 2}
- {name: Matt Deeds, affiliation: 2}
- {name: Jason Trader, affiliation: 2}
- {name: Denali Molitor, affiliation: 1}
- {name: Markus Wulfmeier, affiliation: 3}
- {name: Shawn O'Banion, affiliation: 1}
affiliation:
- {name: Google Research, number: 1}
- {name: Google Maps, number: 2}
- {name: Google DeepMind, number: 3}
link:
- {name: PDF, url: https://arxiv.org/pdf/2305.11290.pdf}
---

![Image name](/assets/worldwide-lift.svg)
*Google Maps route accuracy improvements in several world regions, when using our inverse reinforcement learning policy RHIP.*

<br>
## Abstract
Optimizing for humans' latent preferences is a grand challenge in route recommendation, where globally-scalable solutions remain an open problem. Although past work created increasingly general solutions for the application of inverse reinforcement learning (IRL), these have not been successfully scaled to world-sized MDPs, large datasets, and highly parameterized models; respectively hundreds of millions of states, trajectories, and parameters. In this work, we surpass previous limitations through a series of advancements focused on graph compression, parallelization, and problem initialization based on dominant eigenvectors. We introduce Receding Horizon Inverse Planning (RHIP), which generalizes existing work and enables control of key performance trade-offs via its planning horizon. Our policy achieves a 16-24% improvement in global route quality, and, to our knowledge, represents the largest instance of IRL in a real-world setting to date. Our results show critical benefits to more sustainable modes of transportation (e.g. two-wheelers), where factors beyond journey time (e.g. route safety) play a substantial role. We conclude with ablations of key components, negative results on state-of-the-art eigenvalue solvers, and identify future opportunities to improve scalability via IRL-specific batching strategies.

## BibTeX
```
@article{Barnes2023,
  title = {Massively Scalable Inverse Reinforcement Learning in Google Maps},
  author = {Barnes, Matt and Abueg, Matthew and Lange, Oliver F and Deeds, Matt and Trader, Jason and Molitor, Denali and Wulfmeier, Markus and O'Banion, Shawn},
  journal = {arXiv preprint},
  year = {2023}
}
```
