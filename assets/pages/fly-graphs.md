---
layout: project
title: FLY Graph
permalink: /projects/fly-graphs/
course_it: Architetture Distribuite per il Cloud
course_en: Distributed Architectures for Cloud
repo_name: FLY graph
repo_id: bissim/fly-graph
---

**{{ page.title }}** project purpose is to introduce the _graph_ ADT into the FLY language (a DSL language with multi-cloud support ideated by [Spagnuolo Carmine PhD](https://spagnuolocarmine.github.io/)).

Since FLY compiles over Java, Python and JavaScript (Node.js), **{{ page.title }}** consists of three adapters over three different libraries:

- a Java adapter over the [**JGraphT**](https://jgrapht.org) library;
- a Python adapter over the [**NetworkX**](https://networkx.github.io) library;
- a JavaScript library over the [**graphlib**](https://github.com/dagrejs/graphlib) npm package.

Adapters are needed in order to provide a unique interface for graph handling in FLY.
