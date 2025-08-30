---
title: "Sketch Video Synthesis"
collection: publications
category: manuscripts
permalink: /publication/sketch_video_synthesis
excerpt: ''
date: 2024-08-30
venue: 'Computer Graphics Forum'
authors: 'Yudian Zheng, Xiaodong Cun<sup>*</sup>, Menghan Xia, Chi-Man Pun'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.15044'
projecturl: 'https://sketchvideo.github.io'
githuburl: 'https://github.com/yudianzheng/SketchVideo'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Understanding semantic intricacies and high-level concepts is essential in image sketch generation, and this challenge becomes even more formidable when applied to the domain of videos. To address this, we propose a novel optimization-based framework for sketching videos represented by the frame-wise Bézier Curves. In detail, we first propose a cross-frame stroke initialization approach to warm up the location and the width of each curve. Then, we optimize the locations of these curves by utilizing a semantic loss based on CLIP features and a newly designed consistency loss using the self-decomposed 2D atlas network. Built upon these design elements, the resulting sketch video showcases notable visual abstraction and temporal coherence. Furthermore, by transforming a video into vector lines through the sketching process, our method unlocks applications in sketch-based video editing and video doodling, enabled through video composition.
