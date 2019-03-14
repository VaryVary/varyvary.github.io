---
layout: post
title:  "Uniform Sampling for Configurable Systems"
date:   2018-12-20 011:54:29 +0200
categories: dissemination solving sampling  
---

"Uniform Sampling of SAT Solutions for Configurable Systems: Are We There Yet?" is accepted at [ICST 2019](http://icst2019.xjtu.edu.cn/), the 12th IEEE International Conference on Software Testing, Verification and Validation (a top conference in software testing). 

The answer to the question is in the paper: [preprint is available](https://hal.inria.fr/hal-01991857) ;) 

We are working hard to continue this work. 

```
Uniform or near-uniform generation of solutions for large satisfiability formulas is a problem of theoretical and practical interest for the testing community. Recent works proposed two algorithms (namely UniGen and QuickSampler) for reaching a good compromise between execution time and uniformity guarantees, with empirical evidence on SAT benchmarks. In the context of highly-configurable software systems (e.g., Linux), it is unclear whether UniGen and QuickSampler can scale and sample uniform software configurations. In this paper, we perform a thorough experiment on 128 real-world feature models. We find that UniGen is unable to produce SAT solutions out of such feature models. Furthermore, we show that QuickSampler does not generate uniform samples and that some features are either never part of the sample or too frequently present. Finally, using a case study, we characterize the impacts of these results on the ability to find bugs in a configurable system. Overall, our results suggest that we are not there: more research is needed to explore the cost-effectiveness of uniform sampling when testing large configurable systems.
```


