---
layout: page
title: Performance Evaluation and Wing Deformation Analysis of Flapping-Wing Aerial Vehicles with Varying Flapping Parameters and Patterns
# description: This project is my research topic.
img: /assets/img/ornibibot-jrm.png
importance: 2
category: Academic
related_publications: no
---

<style>
.rotate-video {
    transform: rotate(-90deg);
    /* Additional styles to handle the layout after rotation */
    margin: auto;
}
</style>

<!-- <div class="col-sm mt-3 mt-md-0 rotate-video" style="max-width: 320px;">
    {% include video.html path="assets/video/agressive.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div> -->

### Author
Muhammad Labiyb Afakh, Hidaka Sato, and Naoyuki Takesue

## Abstract
There has been significant interest in the field of bio-inspired robotics, particularly in the development of flapping-wing robots from micro to bird size. Most flapping robots use lever-crank mechanisms or servo motors as wing flapping mechanisms. Servo motor based flapping has the advantage of being able to generate various flapping patterns according to amplitude, offset, frequency, waveform, and other factors. However, it is not clear how these factors affect thrust generation. Therefore, this study focuses on the force generation and power consumption in different flapping patterns as well as the wing deformation during the flapping motion to provide some insights into the performance improvement. The results showed that the response characteristics of the actuators caused the thrust to saturate at high frequencies, and that sinusoidal pattern could generally achieve good performance and efficiency.

## Contribution:
1. Performance is evaluated by varying the basic flapping parameters, such as amplitude, offset, and frequency, as well as the flapping patterns for flapping robots. This is important for single-actuator flapping robots because the only parameter that can be changed is the flapping frequency.
2. Wing deformation is analyzed by varying the flapping parameters and flapping patterns of the flapping robot. The wing is deformed around the flapping axis and the feathering axis. In the flapping axis, reduced amplitude and phase lag appear in the commanded angle to the motor, the actual angle, and the angle of each part of the wing. In the feathering axis, twisting deformation is observed, which affects the thrust as the angle of attack (AoA).


<!-- Skills: Linux, C, C++, Python, ROS1/ROS2, CAD, CAM, EDA, Serial Communication, Git. -->

## System
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/system.png" class="img-fluid rounded z-depth-1" %}
</div>

## Infrastructure
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/infra.png" class="img-fluid rounded z-depth-1" %}
</div>

Repositories of this project is [High level](https://github.com/labiybafakh/OrnibiBot) and [low-level](https://github.com/labiybafakh/OrnibiBotMicro)