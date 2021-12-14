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
<img src="/images/distributed_detection.png" alt="drawing" width="800"/>
</p>

<div style="text-align: justify"> Distributed detection, which arose from multi-radar object detection, has gained its flourishing with the development of wireless sensor networks (WSNs). It is now widely applied in WSNs-based event detection, e.g., spectral sensing in cognitive radio networks, distributed intrusion detection systems, and distributed detection of human activities. 
 </div>

<div style="text-align: justify"> In this project, we consider a multi-stage distributed detection scenario, where n sensors and a fusion center are deployed to accomplish a binary hypothesis test. At each time stage, local sensors generate binary messages and then upload them to the FC for global detection decision making. We suppose a one-bit memory is available at the FC to store its decision history and focus on developing iterative fusion schemes. We first visit the detection problem of performing the Neyman-Pearson test at each stage and give an optimal algorithm, called the oracle algorithm, to solve it. Noticing the computational inefficiency of the oracle fusion, we then propose a low-complexity alternative, for which the likelihood ratio test threshold is tuned in connection to the fusion decision history compressed in the one-bit memory. The low-complexity algorithm greatly brings down the computational complexity at each stage from O(4^n ) (worst case) to O(n). We show that two algorithms exponentially converge to the same performance with the increase of time stages. In addition, the rates of convergence are proven to be asymptotically identical. The proposed low-complexity algorithm is applied in real experiments of done detection using multiple acoustic sensors. Experiment results show that the one-bit information can effectively improve detection performances. 
</div>

## Localizability with Range-Difference Measurements: Numerical Computation and Error Bound Analysis

In this project, we study the source localization problem based on range-difference measurements, or equivalently time difference of arrival (TDOA) measurements. TDOA is a high-precision localization technique and has various applications, ranging from the global positioning system, cellular network localization to under-water sonar positioning. In TDOA-based localization, there is a reference sensor, and for each other sensor, the TDOA measurement is obtained with respect to the reference one. By minimizing the sum of spherical least squares errors, a nonconvex constrained least squares (CLS) problem is constructed. To the best of our knowledge, there is no literature giving a complete algorithm to calculate the global minimizer of this CLS problem. We first derive a set of theoretical results on the existence of a global solution and its explicit characterizations. We then develop an efficient algorithm to solve the CLS problem based on our theoretical findings. We also propose guidelines on sensor deployment to improve localization accuracy. Simulation and real-world experiments in our system demonstrate significant localization error drop compared with existing algorithms.

<p align="center">
<img src="/images/UWB_localization.png" alt="drawing" width="400"/>
<img src="/images/localization_result.png" alt="drawing" width="400"/>
</p>
<p align="center">
    <em>Test on a pubilc UWB-based dataset</em>
</p>