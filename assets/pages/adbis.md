---
layout: project
title: AdBis
permalink: /projects/adbis/
course_it: Integrazione Dati su Web
course_en: Web Data Integration
repo_name: AdBis
repo_id: bissim/adbis
---

**{{ page.title }}** is the sample project developed to apply knowledge acquired from _Web Data Integration_ lectures; the aim was to gather information from several web sources and propose it to users like they were from a single source.

AdBis is an ebook and audiobook aggregator that offers to its users the chance to buy books from several e-commerce web sites by just making their queries to a single web site.

The available sources are:

- [Amazon](http://www.amazon.it/), [Kobo](http://www.kobo.com/) and [Google Books](https://play.google.com/store/books) (via API) for *ebooks*;
- [Audible](http://www.audible.it/) and [ilNarratore](https://www.ilnarratore.com/it/) for *audiobooks*;
- [QLibri](http://www.qlibri.it/) for *reviews*.

Project architecture is based on a mediator among the above-mentioned sources. Previously retrieved results are stored into a database acting like a cache.

To determine whether a result was similar to user queried keyword, we implemented a similarity metric based on [Jaccard index](https://en.wikipedia.org/wiki/Jaccard_index) which is a value in ``[0, 1]`` range that express how much similar two strings are.

Backend has been written in object-oriented **PHP** 7; to cache data about previous search results, **MySQL** RDBMS has been used; front-end interface has been developed with **Bootstrap**.

For further references, read project README.
