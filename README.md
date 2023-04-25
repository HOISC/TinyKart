# TinyKart

Small scale autonomous race car project with obstacle avoidance using STM32 Nucleo H723ZG board, a LIDAR, and a traxxas slash 1/10-scale 2WD RC car. The receiver is removed and replaced with the H732ZG board, which controls both the servo and ESC on the car through PWM.

An ld06 LIDAR is used to get distances infront of the car and the H723ZG processes this data and decides what PWM signals to output to the servo and ESC. A follow-the-gap algorithm is used to do this.
