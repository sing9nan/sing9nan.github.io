---
name: Flight Controller for Underwater Vehicles
tools: [Sensor Fusion, PID Control, Gazebo]
image: /images/mypixhawk/mypixhawk_pcb.png
description: A system to assist the pilot to control ROV 
---

# Flight Controller for Underwater Vehicles

This project is aiming to develop a controller that assist the ROV pilot to drive the underwater vehicle, allowing the pilot to focus on mission tasks rather than manual vehicle control.

First stage (Sensor Fusion validation):\
To gain a better understanding of how sensor fusion works, I first prototyped a Kalman Filter algorithm for orientation estimation using Arduino and MPU9250 in MATLAB.\
<img src="/images/mypixhawk/test1.png" width="200">

<img src="/images/mypixhawk/yaw1.png" width="400">
Without filtering, noise accumulated and the orientation estimation drifted significantly over time. Also, the estimation noise in the EKF model is much less.

Second stage (Hardware Design):\
Designed an embedded system with RTOS integrating BLDC thruster control, IMU and external depth sensors. Also, ported the Kalman Filter algorithm to C and deployed on STM32.

<img src="/images/mypixhawk/RTOS_system.jpg" width="400">
<img src="/images/mypixhawk/mypixhawk_pcb.png" width="400">
Third stage (PID control validation):\
Due to time constraints and the pandemic, I did not have access to a swimming pool for testing. I decided to prototyped the PID controller in Python and verified it through Gazebo simulation. I used the Virtual RobotX (VRX) environment and configured the surface vehicle with vectored thrusters to support my development. In disturbed environments, the algorithm successfully performed stabilization function.
<iframe src="https://drive.google.com/file/d/1Wm-bSYL4hnLtXBdCd9sYveXRUqm4ZSDO/preview" width="854" height="480" allow="autoplay"></iframe>

<object data="/Flight Controller report.pdf" width="100%" height="1000" type='application/pdf'></object>