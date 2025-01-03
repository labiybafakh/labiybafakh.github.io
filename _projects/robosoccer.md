---
layout: page
title: Navigation of Omnidirectional Mobile Robot(Robot Soccer)
# description: a project that redirects to another website
img: assets/img/navigation.png
# redirect: https://unsplash.com
importance: 4
category: Academic
---

This bachelor thesis project is triggered by an idea to recover a navigation when there is an obstacle or hits another robot. A robot simulation(V-
REP) was used to simulate the robot locomotion to implement bicycle path tracking. Robot's position/odometry data is calculated by using 3 rotary encoders. PID controllers are used to control the speed of each motor on its low-level hardware and to control the robot orientation. A fuzzy logic controller is used to change or improve some parameters during navigating such as look-ahead of robot during performing path
tracking and velocity of the robot. By using a given path and gave a force to the robot, the robot was succeeded to
back to its right path smoothly. The performance is better after the fuzzy was implemented because it can reduce
the overshoot. Robotics Operating System(ROS) utilize the robustness of system through the data distribution.

This project repository is [here](https://github.com/labiybafakh/FuzzyBicyclePathTracking)

Contribution:
1. Develop embedded system to measure robot position or odometry by given rotary encoder data and Inertial data.
2. Develop embedded system to control motor speed by using PID controller.
3. Develop robot's system to communicate between low-level and high-level controller.
4. Develop robot navigation using the proposed bicycle path tracking and compare with pure pursuit.
5. Improve the performance of bicycle path tracking by implementing fuzzy controller.

Skills: C, C++, STM32, Arduino, Embedded System, ROS, PID and Fuzzy Controller, Qt.

### Simulation
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/simulasi.png" class="img-fluid rounded z-depth-1" %}
</div>

### Navigation Video
<div style="text-align: center;">
    <iframe width="800" height="450" src="https://www.youtube.com/embed/8nfgbyg1_oo?si=s4w6I5L58vYFpDCU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### System (Rqt Graph on ROS)
<div class="col-sm mt-3 mt-md-0" style="max-width: 560px; margin: auto;">
    {% include figure.html path="assets/img/rqt.jpg" class="img-fluid rounded z-depth-1" %}
</div>
That figure shows the system diagram of this project.