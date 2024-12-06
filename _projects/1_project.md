---
layout: page
title: Study Towards a Flapping Robot Maintaining Attitude During Gliding
# description: This project is my research topic.
img: /assets/img/ornibibot-master.png
importance: 3
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

### Author
Muhammad Labiyb Afakh, Hidaka Sato, Naoyuki Takesue

## Abstract
The bio-inspired robot is such a topic that has received growing attention. The ornithopter micro aerial vehicle (MAV) is a challenging topic for  bio-inspired  robots.  This topic  combines the research  disciplines of  Biology,  robotics,  and  aeronautics. Energy efficiency is one of the advantages offered by a flapping robot. Such a flapping robot can glide to perform locomotion to reduce power consumption. We investigated and developed a flapping robot with tail control to maintain the robot's attitude during locomotion/flight, especially gliding.  The  proposed  tail structure mimics  an  airplane elevator.  Lightweight materials  and  design  are  considered  in  this study. The system is designed to allow the robot to have long-range wireless control. The robot can be wirelessly controlled from a base station via a Wi-Fi connection. This study compares a small wing with good stiffness and a large wing with less stiffness. The small wing with good stiffness is better and could generate thrust 1.56 times higher than the large wing. A large wing's leading and trailing edges bending during flapping can be a possible source of induced drag. Gliding performance was also evaluated. The robot could glide up to 8 meters in 2 seconds at 0.9 meters altitude. The developed robot demonstrated an aggressive flight that reached close to 5 m/s. The developed tail mechanism and controller were confirmed that helps the robot maintain its attitude and recover from a stall within a few milliseconds.

This work is part of my master thesis.
<div class="col-sm mt-3 mt-md-0 rotate-video" style="max-width: 320px;">
    {% include video.html path="assets/video/agressive.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div>


## System
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/ornibibot-master-system.png" class="img-fluid rounded z-depth-1" %}
</div>

## Developed Robot
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/ornibibot-master.png" class="img-fluid rounded z-depth-1" %}
</div>

Repositories of this project is [High level](https://github.com/labiybafakh/OrnibiBot) and [low-level](https://github.com/labiybafakh/OrnibiBotMicro)

{% cite Afakh2023 %}