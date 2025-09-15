---
name: Modularized electronic backplane system
tools: [Embedded System, Circuit Design]
image: /images/rov/backplane/rov_electronics.jpg
description: A modularized electronic system for underwater vehicle
---
# Modularized electronic backplane system

Electronic backplane system was designed to improve the management on different subsystems. It allows for the integration of new features through additional daughter boards, without modifying the main electronic structure. It also enhances the debuggability of the system, allowing the main board to be easily isolated from a faulty subsystem by simply unplugging the daughter board.

__Backplane system Version 1.0__\
<img src="/images/rov/backplane/rov_electronics.jpg" width="500">\
The backplane board provides various communication buses (I2C, UART, SPI) for interfacing with different subsystems, and it also supplies power at multiple voltage levels to support all subsystems.

__Backplane system Version 2.0__\
<img src="/images/rov/backplane/mb2.JPG" width="500">\
The 2.0 design integrated multiple of communcation protocol into a single CAN bus. It also supports a wider power input range (16V-48V), enabling an easier transition from tethered power to battery power.