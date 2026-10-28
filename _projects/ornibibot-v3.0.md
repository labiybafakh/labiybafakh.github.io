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

This work is described in "Servo-Driven Flapping-Wing Aerial Vehicle (FWAV): Payload Capacity and Navigation Performance," published at the 2025 IEEE/SICE International Symposium on System Integration (SII) in Munich, Germany.

### Author
Muhammad Labiyb Afakh, Azhar Aulia Saputra, Hidaka Sato, Kazuyoshi Wada, and Naoyuki Takesue.

<!-- <div class="col-sm mt-3 mt-md-0" style="max-width: 1080px;">
    {% include video.html path="assets/video/payload-and-navigation.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div> -->

<div style="text-align: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/FzHgHGOGEcU?si=Hdl8OR2obr795IRE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

## Abstract
This project investigates how servo-driven flapping-wing aerial vehicles can support environmental monitoring. The robot uses a modular design that allows its wings, tail, and hardware components to be assembled and replaced easily.

We evaluated flapping inputs and found that a square-wave pattern improved performance compared with a sinusoidal pattern. By adjusting the center of gravity and flapping parameters, the robot carried a payload of up to 100 g, approximately 28% of its own weight.

We also implemented a lightweight onboard collision avoidance system to support navigation around obstacles.

## Contribution
1. Developed a modular robot design to simplify transport and maintenance.
2. Improved payload capacity through mechanical and flapping-parameter optimization.
3. Implemented a low-cost, lightweight onboard collision avoidance system.

<!-- Skills: Linux, C, C++, Python, ROS1/ROS2, CAD, CAM, EDA, Serial Communication, Git. -->

## System
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/system-sii2025.png" class="img-fluid rounded z-depth-1" %}
</div>

## Robot
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/robot-sii2025.png" class="img-fluid rounded z-depth-1" %}
</div>

Source code is available in the [OrnibiBot Obstacle Avoidance repository](https://github.com/labiybafakh/OrnibiBotObstacleAvoidance).
