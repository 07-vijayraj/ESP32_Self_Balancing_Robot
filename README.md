# Self Balancing Robot using ESP32

A self balancing robot is a two-wheeled robotic system that can automatically maintain its upright position without external support. This project is built using an ESP32 microcontroller, MPU6050 gyroscope and accelerometer sensor, motor driver, and DC geared motors. The robot continuously senses its tilt angle and instantly moves the wheels in the required direction to prevent falling.

This project combines embedded systems, sensor interfacing, motor control, and control system concepts. It is an excellent practical application of real-time feedback systems and PID control algorithms.

## Project Overview

The main objective of this project is to design and develop a robot that can balance itself on two wheels, similar to an inverted pendulum system. The MPU6050 sensor measures acceleration and angular velocity, and the ESP32 processes this data to calculate the tilt angle. Based on the tilt error, the controller adjusts motor speed and direction to keep the robot balanced.

The ESP32 is selected because of its fast processing speed, built-in WiFi/Bluetooth capability, and easy programming support through Arduino IDE.

## Key Features

- Automatic self balancing in real time
- Fast sensor data processing using ESP32
- PID based closed-loop control system
- Smooth forward and backward correction
- Compact and low-cost design
- Expandable for wireless control
- Suitable for robotics learning and experimentation

## Hardware Components Used

- ESP32 Development Board
- MPU6050 Gyroscope + Accelerometer Module
- Motor Driver Module (BTS7960)
- 2 DC Geared Motors
- Wheels
- Chassis Body
- Rechargeable Battery Pack
- Connecting Wires

## Working Principle

The balancing robot works on the principle of feedback control.

1. The MPU6050 continuously measures tilt angle and angular velocity.
2. ESP32 reads sensor data through I2C communication.
3. Sensor values are filtered and processed.
4. PID algorithm calculates correction output.
5. Motor driver receives PWM signals.
6. Motors rotate forward or backward.
7. The robot regains balance and remains upright.

This process repeats many times every second for continuous balancing.

## PID Controller

PID (Proportional Integral Derivative) control is the core of this project.

- **Proportional (P):** Reacts to present tilt error.
- **Integral (I):** Corrects previous accumulated error.
- **Derivative (D):** Predicts future movement and reduces oscillation.

By tuning PID values properly, the robot becomes stable, responsive, and smooth.

## Applications

- Robotics research
- Control systems demonstration
- Smart transport concepts
- Educational projects
- AI robotic platforms
- Balance mechanism testing
- Embedded systems practice

## Future Improvements

- Bluetooth mobile app control
- Obstacle detection using ultrasonic sensor
- Voice command support
- Camera integration
- ROS connectivity
- Path following mode
- Autonomous navigation

## Conclusion

This self balancing robot project is a strong example of practical embedded engineering. It demonstrates real-time sensing, intelligent control, and motor actuation in one system. It is highly useful for students and engineers interested in robotics, automation, IoT, and control systems.

## Author

Vijay Raj
