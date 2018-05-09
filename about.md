---
layout: page
title: About
permalink: /about/
---

[VaryVary](http://www.agence-nationale-recherche.fr/Projet-ANR-17-CE25-0010) is a 4-year research project funded by the French National Research Agency (ANR).
The goal is to explore the use of artificial intelligence (including machine learning) for playing with software variability present in almost all real-world systems.     

Most modern software systems (operating systems like Linux, Web browsers like Firefox or
Chrome, video encoders like x264 or ffmpeg, etc.) are subject to variation or come in many **variants**. Hundreds of configuration options, features, or plugins can be combined, each potentially with distinct functionality and effects on execution time, memory footprint, etc. Among configurations, some of them are chosen and do not compile, crash at runtime, do not pass a test suite, or do not reach a certain performance quality (e.g., energy consumption, security).

In this project, we follow a thought-provoking and unexplored direction: We consider
that the variability boundary of a software system can be specialized and should itself vary when
needs be. The goal of this project is to provide theories, methods and techniques to make vary variability.
Specifically, we consider **machine learning** and **software engineering** techniques for
narrowing the space of possible configurations to a good approximation of those satisfying
the needs of users. Based on an oracle (e.g., a runtime test) that tells us whether a given configuration meets the requirements (e.g. speed or memory footprint), we leverage machine learning to retrofit the acquired constraints into a variability model that can be used to automatically specialize the configurable system.
Based on a relative small number of configuration samples, we expect to reach high accuracy for many different kinds of oracles and subject systems.

The variation of variability can impact popular, real-world projects and help both end-users and professional developers to fully exploit variability.
In complement to our method, we aim to build an open and collaborative platform for producing and sharing experimental data:
scientists will confront and devise solutions for exploiting variability data the contributors collaboratively supply.
