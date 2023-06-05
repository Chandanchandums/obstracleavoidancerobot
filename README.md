# Obstracle avoidance Robot
Obstracle Avoidance , fire and light detection robot

## Project Description:
This robot is built with an Arduino development board on which microcontroller is placed.
Arduino board is connected with DC Motor through Motor driver which provides power to
the actuators. Actuators are used to move robot in Forward, Backward, Left and Right
directions.
The robot shows a warning in the form of flashing led when heat/fire is detected and also
detects when it is placed in the dark or light and gives feedback in the form of led
(analogous to auto turn on/off headlights).

 
## Sensors used 
1. Ultrasonic sensor: Used to detect presence of obstacles along the path of the robot
and trigger the motor driver via the Arduino to change direction.
2. Light sensor: Used to detect presence of light and trigger the LED to turn on/off
depending on the level of darkness.
3. Flame sensor: Detects heat/fire close to the robot and triggers a warning signal in the
form of flashing led.

## Working of the project:
- The movement of robot is stopped whenever there is an obstacle is present on its path
which is detected by ultrasonic sensors.
- Ultrasonic sensors give time in length to the microcontroller as a input for further actions.
- Action is predefined stop->slightly move back->check right->move



## Requirements 
- Aurdino board
- Bread Board
- Motors
- jumper wires
- Power supply
