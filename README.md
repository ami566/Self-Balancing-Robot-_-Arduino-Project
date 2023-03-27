This code is an Arduino sketch that implements a Proportional-Integral-Derivative (PID) controller to stabilize a self-balancing robot using data from a MPU6050 6-axis motion sensor. The robot uses two motors controlled by an L298N motor driver, and the PID controller uses the motor speed as the output.

## Requirements
To use this code, you will need:

Arduino IDE,
MPU6050 6-axis motion sensor,
L298N motor driver,

## Libraries
This code uses the following libraries:

MPU6050_6Axis_MotionApps20.h,
I2Cdev.h,
PID_v1.h,
LMotorController.h

## Wiring
<img src="Screenshot 2023-03-27 180602.png" width="300" height="350">

## Usage
Upload the code to your Arduino board and ensure the board is properly wired to the sensors and motor controller. The robot should automatically balance itself using the PID controller.
