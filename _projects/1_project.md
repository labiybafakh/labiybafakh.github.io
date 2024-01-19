---
layout: page
title: Ornibibot, an agile flapping micro aerial vehicle (FMAVs)
# description: This project is my research topic.
img: /assets/img/ornibibot.jpg
importance: 1
category: work
related_publications: no
---

This project develops an ornithopter that can be a helpful robot for future in the society. This project is a part of my academic path from
master student to PhD student(now).

• I built my robot from scratch. I designed and manufactured the mechanism and electrical circuit board. I also
built the embedded system and GUI/visualization.

• The previous version robot used ROS 1 as the data distribution system framework. A Wireless connectivity
was chosen to enable long-distance control. A Raspberry Pi-Zero was used to handle the communication with
the base station and low-level controller . An Arduino Nano 33 BLE which is a low-level controller was used to
support the system and control the attitude of robot by using PID controller. Those master and slave hardware
are connected via serial communication.

• The current version uses ROS2. A teensy 4.1 which is a powerful ARM microcontroller was used to support the
data acquisition. The collected data from teensy is sent to the PC using created serial communication protocol
in a low-latency. There is a node to handle the data to be integrated with another ROS2 sub-system or IPC
through shared-memory. A local 5G connectivity will be developed to support long-distance control.

Repositories of this project is [High level](https://github.com/labiybafakh/OrnibiBot) [low-level](https://github.com/labiybafakh/OrnibiBotMicro)

<!-- <div class="row mt-3">
    {% include video.html path="https://www.youtube.com/watch?v=8nfgbyg1_oo" class="img-fluid rounded z-depth-1" %}
</div> -->


