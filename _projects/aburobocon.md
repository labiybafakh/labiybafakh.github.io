---
layout: page
title: ABU Robocon 2016
# description: a project with a background image and giscus comments
img: assets/img/robocon.jpg
importance: 2
category: Competition
# giscus_comments: true
---

In this project, I and my team were trying to build mobile robot to handle or to solve the
tasks. We built 2 autonomous robot with different size, the small robot could not move by itself and has only a
steering mechanism. Several iteration of robot development from scratch were done.The bigger robot has to drive the
small robot without making contact. After the robot is succeeded to drive the small robot, the bigger robot should
pick the propeller that is mounted on small robot, climb a pole, and place the propeller on the pole. That figure shows the robot that I worked on. By using rotary encoder feedback, odometry and inertial data are collected. Those data is used for path tracking on low-level controller using STM32F4. 

<div class="col-sm mt-3 mt-md-0" style="max-width: 320px; margin: auto;">
    {% include figure.html path="assets/img/hybrid.jpeg" title="A hybrid robot" class="img-fluid rounded z-depth-1" %}
</div>

Contribution:
1. Build the embedded system.
2. Integrate several feedback sensor and testing.
3. Build robot navigation algorithm using odometry feedback data.
4. Test and optimize robot performance. The robot's performance increased up to 70% from the previous competition.

Skills: C, STM32, Embedded System, Navigation.

### Regional Competition of Indonesia Robocon
<figure class="d-flex justify-content-center align-items-center" style="height: 100%;">
    <div class="rotate-video" style="max-width: 640px;">
        {% include video.html path="assets/video/robocon-regional.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</figure>

### National Competition of Indonesia Robocon
<figure class="d-flex justify-content-center align-items-center" style="height: 100%;">
    <div class="rotate-video" style="max-width: 640px;">
        {% include video.html path="assets/video/robocon-national.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</figure>


### ABU Robocon 2016
<figure class="d-flex justify-content-center align-items-center" style="height: 100%;">
    <div class="rotate-video" style="max-width: 640px;">
        {% include video.html path="assets/video/abu-robocon.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</figure>

