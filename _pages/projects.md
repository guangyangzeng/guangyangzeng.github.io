---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Low-complexity Distributed Detection with One-bit Memory Under Neyman-Pearson Criterion
<p align="center">
<img src="/images/distributed detection.png" alt="drawing" width="800"/>
</p>

In this project, we consider a multi-stage distributed detection scenario, where n sensors and a fusion center are deployed to accomplish a binary hypothesis test. At each time stage, local sensors generate binary messages and then upload them to the FC for global detection decision making. We suppose a one-bit memory is available at the FC to store its decision history and focus on developing iterative fusion schemes. We first visit the detection problem of performing the Neyman-Pearson test at each stage and give an optimal algorithm, called the oracle algorithm, to solve it. Noticing the computational inefficiency of the oracle fusion, we then propose a low-complexity alternative, for which the likelihood ratio test threshold is tuned in connection to the fusion decision history compressed in the one-bit memory. The low-complexity algorithm greatly brings down the computational complexity at each stage from O(4^n ) (worst case) to O(n). We show that two algorithms exponentially converge to the same performance with the increase of time stages. In addition, the rates of convergence are proven to be asymptotically identical. The proposed low-complexity algorithm is applied in real experiments of done detection using multiple acoustic sensors. Experiment results show that the one-bit information can effectively improve detection performances.

