---
layout: page
title: ABU Robocon 2016
# description: a project with a background image and giscus comments
img: assets/img/robocon.jpg
importance: 2
category: work
# giscus_comments: true
---

In this project, I and my team were trying to build mobile robot to handle or to solve the
tasks. We built 2 autonomous robot with different size, the small robot could not move by itself and has only a
steering mechanism. Several iteration of robot development from scratch were done.The bigger robot has to drive the
small robot without making contact. After the robot is succeeded to drive the small robot, the bigger robot should
pick the propeller that is mounted on small robot, climb a pole, and place the propeller on the pole.

<div class="col-sm mt-3 mt-md-0" style="max-width: 320px; margin: auto;">
    {% include figure.html path="assets/img/hybrid.jpeg" title="A hybrid robot" class="img-fluid rounded z-depth-1" %}
</div>

That figure shows the robot that I worked on. By using rotary encoder feedback, odometry and inertial data are collected. Those data is used for path tracking on low-level controller using STM32F4. To put and place propeller on the pole, some dynamixel servos are used on the first prototype that could achieve 36s to finish the task. The improvement on lastest robot could achieve 18s.

Some videos below show the performance and upgrade of robot developed from Regional, National, and Asia-Pasific competiion.

### Regional Competition of Indonesia Robocon
<div class="row mt-3">
    <div class="col-12 col-lg-6 mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
            {% include video.html path="https://www.youtube.com/embed/hRgKo8AS99A?si=CrBEew5nsAjCOT3U" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### National Competition of Indonesia Robocon
<div class="row mt-3">
    <div class="col-12 col-lg-6 mt-3 mt-md-0" style="max-width: 560px !important; margin: auto;">
            {% include video.html path="https://www.youtube.com/embed/Gdd02YA4iVU?si=PQgRZfpojt-UgbMd" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### ABU Robocon 2016
<div class="row mt-3">
    <div class="col-12 col-lg-6 mt-3 mt-md-0" style="max-width: 560px !important; margin: auto;">
            {% include video.html path="https://www.youtube.com/embed/hlAESUCWL_Y?si=53hWgJ2ngytJbNc_" class="img-fluid rounded z-depth-1" %}
    </div>
</div>