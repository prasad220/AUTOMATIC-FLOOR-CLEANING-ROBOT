# AUTOMATIC-FLOOR-CLEANING-ROBOT
Abstract— The entire floor cleaning robot is divided into
several parts, namely consisting of an Ultrasonic Sensor, Motor
Shield L298, Arduino Uno microcontroller, Servo, and Dc
Motor. This tool works when the Arduino Uno microcontroller
processes the ultrasonic sensor as a distance detector and a DC
motor as a robot driver, then the DC motor is driven by the
Motor Shield L298. When an ultrasonic sensor detects a barrier
in front of it, the robot will automatically look for a direction
that is not a barrier to the floor cleaning robot. The distance
value on the sensor has been determined, that is, when the
distance read by the ultrasonic sensor is below 15 cm.
-> If the distance between the robot and obstacle is grater than 15 cm,
the robot goes on cleaning.
-> If the distance between the robot and obstacle is smaller than 15 cm,
the robot tries to find a direction in which the is no obstacle within 
15 cm.
-> The robot goes on doing this until stopped.
 
