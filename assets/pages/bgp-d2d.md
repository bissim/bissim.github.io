---
layout: project
title: BGP D2D
permalink: /projects/bgp-d2d/
course_it: Sistemi Operativi Avanzati
course_en: Advanced Operative Systems
repo_name: BGP D2
repo_id: bissim/bgp-d2
---

**{{ page.title }}** is a distributed library which goal was to calculate similarity matrix of several genomic sequences; the similarity metric used is [D2](https://arxiv.org/abs/0909.1370).

The library has been implemented with Apache Hadoop. Distributed D2 implementation consist of a first MapReduce phase (to read k-mers occurrences from KMC output file and calculate partial D2 scores) and an eventual second one where if more than one task is created to sum partial scores.

For further references, read project README.
