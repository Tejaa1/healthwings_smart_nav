# healthwings_smart_nav
Smart Navigation system for autonomous medical drones using ROS, Pixhawk, GPS, and MAVROS.
# HealthWings Smart Navigation

This ROS-based package enables smart autonomous navigation for medical drones as part of the **HealthWings** project. It integrates Pixhawk flight control, GPS-based waypoint navigation, and radio telemetry for reliable and flexible field deployment in emergency scenarios.

Built to run on a Raspberry Pi 4 (4GB) as the companion computer, this system allows the drone to take off, navigate to GPS coordinates, and return safely — all controlled via ROS nodes and MAVROS.

## Features

- GPS waypoint navigation using MAVROS
- Autonomous arming and takeoff
- Return-to-launch (RTL) capability
- Compatible with Pixhawk running ArduPilot or PX4
- Easy deployment via shell script

## Project Use-Case

This project was developed for **HealthWings**, a smart drone-based solution designed to deliver emergency medical supplies to remote areas using intelligent path navigation and gesture-based control.
