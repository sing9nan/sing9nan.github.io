---
name: Modularized electronic backplane system
tools: [Embedded System, Circuit Design]
image: /images/rov/backplane/rov_electronics.jpg
description: A modularized electronic system for underwater vehicles
---
# Modularized electronic backplane system

Electronic backplane system was designed to improve the management of different subsystems. It allows for the integration of new features through additional daughter boards, without modifying the main electronic structure. It also enhances the debuggability of the system, allowing the main board to be easily isolated from a faulty subsystem by unplugging the daughter board.

__Backplane system Version 1.0__\
<img src="/images/rov/backplane/rov_electronics.jpg" width="500">\
The backplane board provides various communication buses (I2C, UART, SPI) for interfacing with different subsystems, and it also supplies power at multiple voltage levels to support all subsystems.

__Backplane system Version 2.0__\
<img src="/images/rov/backplane/mb2.JPG" width="500">\
The 2.0 design reduced the length of the PCB and rerouted the I/O plugs to the back, freeing up space in front of the electronic compartment to fit in a larger single board computer and stereo cameras. It also integrated multiple communication protocols into a single CAN bus and supported a wider power input range (16V-48V), which enables an easier transition from tethered power to battery power.

__Design Documents__\
<img src="/images/rov/backplane/back_board_sch1.png" width="800">
<img src="/images/rov/backplane/back_board_sch2.png" width="800">
<img src="/images/rov/backplane/mb2_sch1.png" width="800">
<img src="/images/rov/backplane/mb2_sch2.png" width="800">
<img src="/images/rov/backplane/mb2_sch3.png" width="800">
<img src="/images/rov/backplane/back_board_pcb.png" width="800">
<img src="/images/rov/backplane/mb2_pcb.png" width="800">
