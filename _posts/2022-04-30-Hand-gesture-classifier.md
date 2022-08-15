---
title:  Hand gesture Classifier
tags:
  - Software
  - Python
  - Machine Learning
  - Classification
images:
  
---

<!--more-->

As a semester project for a Digital Signal Processing (DSP) and Machine Learning (ML) course, myself and a partner created a hand gesure classifier which would classify one of three gand gesture (go/slow down/stop) based off inertial measurement unit (IMU) data from a smartphone. The report for this project can be found 
[here]({{ site.baseurl}}{% link docs/EEE4114_Project_Report_WHTDYL001_LSXKEE002.pdf %})

In this project we invesigated various features selections for using a k-nearest neighbour algorithm to classify IMU data. We found that for these simple gestures, simple mean acceleration features are sufficient for accurate classification but more advanced feature selection methods such as Dynamic Time Warping may be necessary with the drawback of extended computation times.
