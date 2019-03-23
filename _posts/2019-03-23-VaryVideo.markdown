---
layout: post
title:  "Variability in the Video Domain"
date:   2019-03-23 011:54:29 +0200
categories: publication video synthesis 
---


The article "Modeling Variability in the Video Domain: Language and Experience Report" has been (finally) published in a journal issue of the Software Quality Journal (Springer journal). 
It's a joint work with colleagues at University of Sevilla (Jose Galindo and David Benavides).  
This paper has a long story: in 2014 (yes, 5 years ago) we published a [technical report](https://hal.inria.fr/hal-01023159) about our language. 
Since then, we have continuously improved the article, maybe more emphasizing the process and the underlying difficulties of modeling variability.
Anyway, it's available [online](https://link.springer.com/article/10.1007/s11219-017-9400-8) and the [preprint is available](https://hal.inria.fr/hal-01688247). 

We are pursuing the work with the video generator, either for improving its [quality](https://hal.inria.fr/hal-01659137) or for [exploiting video variants](https://hal.inria.fr/hal-01323446).

![Extraction process](/assets/videos.png)

Abstract below:
> In an industrial project, we addressed the challenge of developing a software-based video generator such that consumers and providers of video processing algorithms can benchmark them on a wide range of video variants. 
> This article aims to report on our positive experience in modeling, controlling, and implementing software variability in the video domain. 
> We describe how we have designed and developed a variability modeling language, called VM, resulting from the close collaboration with industrial partners during 2 years. 
> We expose the specific requirements and advanced variability constructs; we developed and used to characterize and derive variations of video sequences. 
> The results of our experiments and industrial experience show that our solution is effective to model complex variability information and supports the synthesis of hundreds of realistic video variants. 
> From the software language perspective, we learned that basic variability mechanisms are useful but not enough; attributes and multi-features are of prior importance; meta-information and specific constructs are relevant for scalable and purposeful reasoning over variability models. 
> From the video domain and software perspective, we report on the practical benefits of a variability approach. With more automation and control, practitioners can now envision benchmarking video algorithms over large, diverse, controlled, yet realistic datasets (videos that mimic real recorded videos)—something impossible at the beginning of the project.






