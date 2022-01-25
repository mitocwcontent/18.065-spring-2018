---
content_type: resource
description: ''
file: null
resourcetype: Video
title: 'Lecture 23: Accelerating Gradient Descent (Use Momentum)'
uid: d701065a-0c65-a65f-846f-2d1b676f9614
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture23_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/558af63ca39950e1b045685768ce8de1_wrEcHhoJxjM.vtt
  video_thumbnail_file: https://img.youtube.com/vi/wrEcHhoJxjM/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/30baaee029e0f6821d48b6397fcca1d0_wrEcHhoJxjM.pdf
video_metadata:
  youtube_id: wrEcHhoJxjM
---

**Description**
---------------

In this lecture, Professor Strang explains both momentum-based gradient descent and Nesterov's accelerated gradient descent.

**Summary**
-----------

Study the zig-zag example: Minimize \\(F = \\frac{1}{2} (x^2 + by^2)\\)  
Add a momentum term / heavy ball remembers its directions.  
New point \\(k\\) + 1 comes from TWO old points \\(k\\) and \\(k\\) - 1.  
"1st order" becomes "2nd order" or "1st order system" as in ODEs.  
Convergence rate improves: 1 - \\(b\\) to 1 - square root of \\(b\\) !

Related section in textbook: VI.4

**Instructor:** Prof. Gilbert Strang