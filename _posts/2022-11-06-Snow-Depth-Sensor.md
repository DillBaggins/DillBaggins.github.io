---
title:  Undergraduate Thesis - Investigation into technologies for the development of a remote snow depth sensor
tags:
  - Mechatronics
  - MATLAB
  - Simulink
  - C
  - Hardware Design
  - Signal Processing
images:
  - \photos\thesis\../photos/thesis/ultrasonic-board.png
  
---
<div class="card mb-3">
    <img class="img-thumbnail" src="\photos\thesis\ultrasonic-board.png"/>
    <div class="card-body bg-light">
    </div>
</div>

<!--more-->

For my undergraduate thesis, I was tasked with the investigation of various techniques for the in-situ measurement
of snow accumulation. This was to be achieved by identifying effective techniques/devices that can measure distance to snow from a fixed point. 

Two primary methods were investigated, these being time-of-flight ranging via the use of an ultrasound sensor and the use of a VL53l1X commercial laser ranging sensor from ST Microelectronics.

In the process of this project, an ultrasonic sensor was developed from the ground up and an
embedded system was developed for interfacing with both this developed sensor as well as the
commercial laser ranging sensor.

Tests were performed on each of these sensors under a variety of environmental conditions
attempting to emulate those that would be encountered in the in-situ measurement of snow accumulation. These tests yielded data illustrating the performance of each of these measurement techniques across an array of environmental conditions.

This data was then used to quantify and determine each sensor’s performance and applicability
to the problem of snow accumulation measurement. It was found that, under low ambient light
conditions, the laser sensor could achieve an accuracy of 1.56±1.17cm while the performance
of the ultrasonic sensor in a time-of-flight configuration was too variable to quantify a single
performance result.

I enjoyed this project and gained a lot from it. I particularly enjoyed it because it allowed me to utilise skills from difference facets of my education; from basic analog hardware design to programming and signal processing. Those interested in reading the full report can find it [here]({{ site.baseurl}}{% link docs/EEE4022S 2022 FINAL REPORT WHTDYL001 White DP - Verrinder.pdf%})

