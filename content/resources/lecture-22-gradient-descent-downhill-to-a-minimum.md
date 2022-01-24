---
content_type: resource
description: ''
file: null
resourcetype: Video
title: 'Lecture 22: Gradient Descent: Downhill to a Minimum'
uid: 4318cf43-b3aa-08b7-9564-f2376a48f586
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture22_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/bbd9ccb8a7965b449b01e6d50e3c7605_AeRwohPuUHQ.vtt
  video_thumbnail_file: https://img.youtube.com/vi/AeRwohPuUHQ/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/b73b070e30b2d7f2a88e07ca72c42eaa_AeRwohPuUHQ.pdf
video_metadata:
  youtube_id: AeRwohPuUHQ
---

**Description**
---------------

Gradient descent is the most common optimization algorithm in deep learning and machine learning. It only takes into account the first derivative when performing updates on parameters—the stepwise process that moves downhill to reach a local minimum.

**Summary**
-----------

Gradient descent: Downhill from \\(x\\) to new \\(X = x - s (\\partial F / \\partial x)\\)  
Excellent example: \\(F(x,y) = \\frac{1}{2} (x^2 + by^2)\\)  
If \\(b\\) is small we take a zig-zag path toward (0, 0).  
Each step multiplies by \\((b - 1)/(b + 1)\\)  
Remarkable function: logarithm of determinant of \\(X\\)

Related section in textbook: VI.4

**Instructor:** Prof. Gilbert Strang