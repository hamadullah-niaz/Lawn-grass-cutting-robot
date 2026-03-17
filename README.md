# Lawn Grass Cutting Robot

## Overview
This was my term project where I designed and built a lawn grass cutting robot using Arduino. The goal was to create a small robotic system that can move across a lawn and cut grass using a motorized cutting mechanism.

## What the robot does
The robot moves across the lawn using DC motors. A sensor placed at the front detects the presence of grass. When grass is detected, the cutting motor is activated. When no grass is detected, the robot changes direction and continues searching for grass.

## Hardware Used
- Arduino Uno
- L293D Motor Driver Shield
- IR based detection sensor
- DC motors for movement
- DC motor for grass cutting blade
- Battery pack
- Chassis with wheels

## How it works
The Arduino controls the movement of the robot through the motor driver shield. The sensor continuously checks the surface in front of the robot.

- Grass detected → robot moves forward + cutter ON  
- No grass → cutter OFF + robot changes direction  

This allows the robot to cover different areas of the lawn.

## Project Images
(Add images below)

## Challenges
- Sensor accuracy in outdoor conditions
- Power management for motors and cutting blade
- Mechanical stability of the cutting system

## What I learned
- How to interface motors with Arduino
- Basics of motor driver circuits
- Real-world issues in robotics (not everything works perfectly like theory)
- Importance of testing and iteration
