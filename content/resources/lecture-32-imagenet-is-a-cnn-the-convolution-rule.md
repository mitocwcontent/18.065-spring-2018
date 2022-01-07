---
content_type: resource
description: ''
file: null
resourcetype: Video
title: 'Lecture 32: ImageNet is a Convolutional Neural Network (CNN), The Convolution
  Rule'
uid: 0197a0ae-0870-f75f-49cb-fbe02e9e65a9
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture32_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/bce815326359585daa637823cd6e6a46_hwDRfkPSXng.vtt
  video_thumbnail_file: https://img.youtube.com/vi/hwDRfkPSXng/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/f05ad51e5ee027dee95a998604e0dfdf_hwDRfkPSXng.pdf
video_metadata:
  youtube_id: hwDRfkPSXng
---

Description
-----------

Professor Strang begins the lecture talking about ImageNet, a large visual database used in visual object recognition software research. ImageNet is an example of a convolutional neural network (CNN). The rest of the lecture focuses on convolution.

Summary
-------

Convolution matrices have \\(\\leq\\) \\(n\\) parameters (not \\(n\\)2).  
Fewer weights to compute in deep learning  
Component \\(k\\) from convolution \\(c\*d\\): Add all \\(c(j)d(k-j)\\)  
Convolution Rule: \\(F(c\*d) = Fc\\) times \\(Fd\\) (component by component)  
\\(F\\) = Fourier matrix with \\(j\\), \\(k\\) entry \\(= \\exp (2 \\pi i j k /n)\\)

Related section in textbook: IV.2

**Instructor:** Prof. Gilbert Strang