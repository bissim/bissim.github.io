---
layout: project
title: MPEG Scrambling
permalink: /projects/mpeg-scrambling/
course_it: Compressione Dati
course_en: Data Compression
repo_name: MPEG Scrambling
repo_id: bissim/mpeg-scrambling
---

**{{ page.title }}** is a modified implementation of PVRG MPEG which goal is to hide people's faces for privacy purposes; this is done by applying the *scrambling* technique consisting into randomly modifying pixels within the region of interest.
Face detection is achieved through OpenCV library and face detection strategies.

Original project has been led by Leo Aniello and Lorenzo Vitale; in particular, Lorenzo Vitale originally introduced face detection and scrambling implementation in Java.

The BRS team I was member of dealt with transposing the Java code into C++ in order to reduce overhead due to repeated system calls to run JVM; this porting led to an average reduction of time execution of about 80%.
