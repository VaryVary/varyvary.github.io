---
layout: post
title:  "Tutorial at ASE 2018 Re-engineering Software Variability into Software Product Lines"
date:   2018-09-03 011:54:29 +0200
categories: dissemination 
---

Mathieu Acher gave a tutorial (~20 participants) at [Automated Software Engineering conference (ASE 2018)](http://www.ase2018.com/?p=tutorials#spl), with Tewfik Ziadi (Sorbonne Université, LIP6)
about Re-engineering Software Variability into Software Product Lines. 

Software Product Lines (SPLs) represent one of the most exciting paradigm shift in software development in the two last decades. Multiple approaches have been proposed addressing the different activities of variability design and manipulation, reusable assets implementation, or product derivation.
However, adopting an SPL approach and managing variability is still a major challenge and represents a risk for a company. First, compared to single-system development, SPL variability management implies a methodology that highly impacts the life cycle of the products as well as the processes and roles inside the company. Second, adopting an SPL from the beginning, called proactive SPL adoption, is subject to two main assumptions: 1) these companies must have, in advance, a complete understanding of the variability to anticipate all possible variations; 2) these companies should start from scratch to specify the variability and implement the reusable assets. Thus, instead of adopting an SPL, many companies usually start from a set of existing systems that must undergo a well-defined re-engineering process. Many approaches to conduct such re-engineering processes have been proposed and documented in research literature.
In this tutorial, after introducing SPLs and their concepts, we introduce the re-engineering processes for SPL adoption and a summary of the research literature. Attendees will have the possibility to experiment hands-on with SPL open source tools and also on our tools for SPL re-engineering such as FAMILIAR and BUT4Reuse.

The tutorial is structured as follows:

# Come, let's play with Software Product Lines. 

We will use two intuitive examples: a generator of LaTeX paper variants (VaryLaTeX) and a programming game-rich variability system (Robocode). These two examples will be an opportunity to present the general process of SPL engineering: (1) feature modeling (2) variability implementation (3) product derivation. We will use open source tools with exercises we used when training graduate students and PhD candidates (see http://teaching.variability.io/)

## Part 1: Course
Domain analysis and feature model specification including feature identification, hierarchical organisation of features, constraints, and hot research topics).
Domain Implementation including main existing paradigms (annotative, compositional) in different technologies (e.g, Java, JavaScript).
Product Derivation for automating the synthesis of variants.
## Part 2: Hands-on experiments
FAMILIAR (https://familiar-project.github.io) for elaborating and reasoning about feature models.
Analysis of SPL implementation of open source projects.

# SPL re-engineering. 

Now the audience is convinced by the benefits of an SPL approach, we introduce the general re-engineering process including the different activities related to: (1) feature identification and location (2) constraint mining (3) reusable asset extraction (4) variability model synthesis.

## Part 1: Course
Extractive SPL adoption activities including feature Identification and location, constraints mining, reusable assets and feature model extraction.
Machine learning based techniques for automatically extracting constraints.

## Part 2: Hands-on experiments
Extracting SPL from existing variants using the BUT4Reuse platform. We will use the examples and the benchmarks provided by the BUT4Reuse platform (https://github.com/but4reuse/but4reuse/wiki/Examples).
Mining constraints with statistical, supervised machine learning (https://varyvary.github.io/): we will use an end-to-end example with VaryLaTeX for learning paper variants that meet constraints.
