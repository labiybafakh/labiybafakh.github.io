---
layout: page
title: Servo-Driven Flapping-Wing Aerial Vehicle (FWAV) Payload Capacity and Navigation Performance
# description: This project is my research topic.
img: /assets/img/robot-sii2025.png
importance: 1
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

This study has been accepted for The 2025 IEEE/SICE International Symposium on System Integration. It will be presented on January in Munich, German.

### Author
Muhammad Labiyb Afakh, Azhar Aulia Saputra, Hidaka Sato, and Kazuyoshi Wada, Naoyuki Takesue

<!-- <div class="col-sm mt-3 mt-md-0" style="max-width: 1080px;">
    {% include video.html path="assets/video/payload-and-navigation.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div> -->

<div style="text-align: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/FzHgHGOGEcU?si=Hdl8OR2obr795IRE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

## Abstract
In the current situation, environmental monitoring and disaster mitigation become a concern. There are many developed robot in different type for
enviromental issue, but some robot has limitation on coverage area. To solve that problem, several researcher also developed FWAV that has
potential on environment monitoring application. This study aims to enhance the potential of Flapping Wing Aerial Vehicles (FWAVs) for wider implementation in these fields. While most FWAVs traditionally use a single actuator, leading to manufacturing and design complexity, recent trends show a shift towards servo-driven mechanisms due to their enhanced capabilities. We achieve modularity through a design that allows for easy assembly and disassembly of main wings, tail, and hardware components. Performance enhancements are realized through the implementation of a square wave pattern as the input signal for flapping motion, which outperforms the common sinusoidal wave pattern as input signal. By adjusting the center of gravity and flapping parameters, we demonstrate the FWAV's potential to carry payloads of up to 100 grams which is almost 28\% of its weight, suitable for small-scale environmental monitoring missions. Additionally, we implement a collision avoidance system to enhance the FWAV's ability to navigate safely in complex environments. 

## Contribution
1. Modular and durable design to make it easy to carry and reduces the maintenance complexity .
2. Fly with payload.
3. A low-cost and lightweight obstacle avoidance.

<!-- Skills: Linux, C, C++, Python, ROS1/ROS2, CAD, CAM, EDA, Serial Communication, Git. -->

## System
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/system-sii2025.png" class="img-fluid rounded z-depth-1" %}
</div>

## Robot
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/robot-sii2025.png" class="img-fluid rounded z-depth-1" %}
</div>

Repositories of this project is [Ornibibot Obstalce Avoidance](https://github.com/labiybafakh/OrnibiBotObstacleAvoidance) 