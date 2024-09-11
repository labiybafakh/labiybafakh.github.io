---
layout: page
title: Ornibibot, an agile flapping micro aerial vehicle (FMAVs)
# description: This project is my research topic.
img: /assets/img/ornibibot.jpg
importance: 1
category: work
related_publications: no
---

<style>
.rotate-video {
    transform: rotate(-90deg);
    /* Additional styles to handle the layout after rotation */
    margin: auto;
}
</style>

<div class="col-sm mt-3 mt-md-0 rotate-video" style="max-width: 320px;">
    {% include video.html path="assets/video/agressive.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div>

This project develops an ornithopter that can be a helpful robot for future in the society. This project is a part of my academic path from
master student to PhD student(now).

Contribution:
1. Develop robot's structure using a light-weight material.
2. Develop robot's hardware using Arduino Nano 33 BLE with Raspberry for the previous version and Teensy 4.1 for the current version.
3. Develop robot's system and visualization utilizing ROS1/ROS2.
4. Implement PID controller with given Inertial Measurement data to perform attitude control using tail mechanism.
5. Improve the performance serial communication by optimizing the packet data so it could work in above 500Hz.
6. Integrate force sensor and motion caption camera to support its analysis.
7. Test the performance native system using shared-memory and compare with ROS2 performance.
8. Currently, developing robot vision system and control to perform obstacle avoidance using point cloud data

Skills: Linux, C, C++, Python, ROS1/ROS2, CAD, CAM, EDA, Serial Communication, Git.

## System
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/system.png" class="img-fluid rounded z-depth-1" %}
</div>

## Infrastructure
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/infra.png" class="img-fluid rounded z-depth-1" %}
</div>

Repositories of this project is [High level](https://github.com/labiybafakh/OrnibiBot) and [low-level](https://github.com/labiybafakh/OrnibiBotMicro)