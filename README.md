# Rover Navigation and Obstacle Avoidance Program README

## Overview
This program is designed for an Arduino-based rover equipped with GPS and magnetometer modules, enabling autonomous navigation towards waypoints. It integrates obstacle detection and avoidance, plus a digging mechanism, leveraging two separate Arduino boards for navigational control and obstacle handling/digging operations respectively.

## Features
- **GPS Navigation**: Utilizes a GPS module to guide the rover along specified waypoints.
- **Compass Heading**: Employs a magnetometer for orientation, ensuring the rover maintains its course.
- **Obstacle Avoidance**: Integrates ultrasonic sensors to detect obstacles, altering the rover's path as necessary.
- **Motor Control**: Manages gear motors for movement and includes functionality for both speed and directional adjustments.
- **Digging Mechanism**: Features a stepper motor-based mechanism for digging operations at designated waypoints.
