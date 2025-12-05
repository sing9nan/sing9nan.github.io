---
name: Pioneer
tools: [Robotics, Computer Vision, ROS]
image: /images/robots/pioneer.jpeg
description: An autonomous underwater vehicle (AUV) with camera and IMU-based navigation. Participated and completed tasks autonomously in IEEE SAUVC
---

# Pioneer
<img src='/images/robots/pioneer.jpeg' width="400">\
Pioneer is an Autonomous Underwater Vehicle (AUV) developed with <a href="https://www.ee.cityu.edu.hk/~rovteam/">CityU Underwater Robotics Team</a>

Hardware:\
Pioneer is designed to perform autonomous tasks underwater. It is equipped with six Blue Robotics T-200 thrusters in a vectored configuration to achieve 6-DoF movement. It is powered by a Jetson Nano, which processes image recognition and perception algorithms using input from a stereo camera. The vehicle is also equipped with a hall-effect-based kill switch, allowing missions to be aborted externally for safety.

Software:\
Pioneer uses a ROS system to communicate across different nodes, enabling more efficient parallel development among teammates and increasing system robustness. A PID-based flight controller with orientation estimation was developed and fine-tuned for Pioneer to perform precise maneuvers. Additionally, an OpenCV-based object detection algorithm was implemented to recognize competition props in underwater environments, allowing the vehicle to perform autonomous tasks.

<iframe src="https://drive.google.com/file/d/1V6pTL5m1c8p9_BjOsE2Uyvdml2CMGa1m/preview" width="540" height="540" allow="autoplay"></iframe>

Competitions:\
<a href="https://sauvc.org/2019/">IEEE SAUVC 2019</a>, Singapore\
<a href="https://sauvc.org/2022/">IEEE SAUVC 2022</a>, Singapore