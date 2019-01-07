STM32-based IMU/Position Compute Board
======================================

This project is attempting to implement a board which, given the inputs from a standard FRC IMU,
can determine the position and heading of an FRC robot, with minimal input or programming required
on the roboRIO.

The processor of choice is an STM32 F4 series (one eqipped with an FPU) because they're cheap
but faster than a comparable AVR.
