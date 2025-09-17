---
name: Pioneer
tools: [Robotics, Computer Vision, ROS]
image: /images/robots/pioneer.jpeg
description: An Autonomous Underwater Vehicle (AUV)
---

# Pioneer
<img src='/images/robots/pioneer.jpeg' width="400">\
Pioneer is a Autonomous Underwater Vehicle (AUV) developed with <a href="https://www.ee.cityu.edu.hk/~rovteam/">CityU Underwater Robotics Team</a>

Hardware:\
Pioneer is designed to perform autonomous tasks underwater. It is equipped with six Blue Robotics T-200 thrusters in a vectored configuration to achieve 6-DoF movement. It is powered by a Jetson Nano, which processes image recognition and perception algorithms using input from a stereo camera. The vehicle is also equipped with a hall-effect-based kill switch, allowing missions to be aborted externally for safety.

Software:\
Pioneer uses a ROS system to communicate across different nodes, enabling more efficient parallel development among teammates and increasing system robustness. A PID-based flight controller with orientation estimation was developed and fine tuned for Pioneer to perform precise maneuvers. We also developed an OpenCV-based object detection algorithm to recognize competition props in underwater environments, allowing the vehicle to perform autonomous tasks.

Competitions:\
<a href="https://sauvc.org/2019/">IEEE SAUVC 2019</a>, Singapore\
<a href="https://sauvc.org/2022/">IEEE SAUVC 2022</a>, Singapore