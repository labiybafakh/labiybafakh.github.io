---
layout: page
title: Navigation of Omnidirectional Mobile Robot(Robot Soccer)
# description: a project that redirects to another website
img: assets/img/navigation.png
# redirect: https://unsplash.com
importance: 3
category: work
---

This bachelor thesis project is triggered by an idea to recover a navigation when there is an obstacle or hits another robot. A robot simulation(V-
REP) was used to simulate the robot locomotion to implement bicycle path tracking. Robot's position/odometry data is calculated by using 3 rotary encoders. PID controllers are used to control the speed of each motor on its low-level hardware and to control the robot orientation. A fuzzy logic controller is used to change or improve some parameters during navigating such as look-ahead of robot during performing path
tracking and velocity of the robot. By using a given path and gave a force to the robot, the robot was succeeded to
back to its right path smoothly. The performance is better after the fuzzy was implemented because it can reduce
the overshoot. Robotics Operating System(ROS) utilize the robustness of system through the data distribution.

[Robot Navigation Video](https://www.youtube.com/watch?v=8nfgbyg1_oo)

A repository of this project is [here](https://github.com/labiybafakh/FuzzyBicyclePathTracking)

### Navigation Video
<div class="col-sm mt-3 mt-md-0" style="max-width: 320px; margin:auto;">
    {% include video.html path="https://www.youtube.com/embed/8nfgbyg1_oo?si=xo37-fjSHm0PutoW&amp;controls=0" class="img-fluid rounded z-depth-0" %}
</div>

### System (Rqt Graph on ROS)
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/rqt.jpg" class="img-fluid rounded z-depth-1" %}
</div>
That figure shows the system diagram of this project.