---
name: Micro ROV
tools: [STM32, Embedded System, Circuit Design]
image: /images/rov/micro_rov/micro_rov.png
description: A micro underwater vehicle smaller than 20x15x10 cm
---

# Micro ROV
<img src="/images/rov/micro_rov/micro_rov.png" width="400">\
Micro ROV was designed to complete [drain pipe inspection](https://youtu.be/74NfNVIC7gQ?si=ROAnxh4pmuXip2_a&t=71) task in [2019 MATE ROV](https://materovcompetition.org/2019-competition-archive). It is equipped with two 25W thrusters, LEDs and an analog camera. The Micro ROV is tethered to the main ROV for power supply and command and video transmission. The embedded system integrated a STM32 MCU, motor drivers, power converter and RS485 communication circuit on a single PCB board (\< 4x4 cm).

<img src="/images/rov/micro_rov/PCB.JPG" width="400">
<img src="/images/rov/micro_rov/pcb_front.JPG" width="200"><img src="/images/rov/micro_rov/pcb_back.JPG" width="200">

__Design Documents__\
<img src="/images/rov/micro_rov/control_sch.png" width="800">
<img src="/images/rov/micro_rov/cam_sch.png" width="800">
<img src="/images/rov/micro_rov/control_pcb.png" width="400">
<img src="/images/rov/micro_rov/cam_pcb.png" width="400">