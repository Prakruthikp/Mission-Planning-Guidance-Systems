Mission Planning & Guidance Systems
Overview

This repository presents the development, integration, simulation, verification, and validation of an autonomous UAV Mission Planning and Guidance System using MATLAB/Simulink, ArduPilot, Mission Planner, and the Cube Orange Flight Control Unit (FCU).

The project focuses on autonomous mission execution, waypoint navigation, FCU-FADEC communication, and software/hardware validation for fixed-wing UAV platforms.

Project Objective

The objective of this project is to develop, integrate, simulate, verify, and validate a Flight Control Unit (FCU) using Cube Orange hardware running ArduPilot.

The FCU communicates with the FADEC through CAN communication and is validated using:

Software-in-the-Loop (SIL)
Hardware-in-the-Loop (HIL)
Ground Testing
Mission Planner
Hardware Configuration
Cube Orange Flight Controller
CUAV NEO 3 GPS
RM3100 Magnetometer
Telemetry Radio
CAN Transceiver
USB Joystick
Flight Battery
Servos
FADEC Controller
Software Stack
MATLAB
Simulink
ArduPilot Plane v4.6.3
Mission Planner v1.3.83
MAVLink
CAN Protocol
Flight Control Architecture

The project integrates:

Flight Control Unit (FCU)
FADEC
Mission Planner
Ground Control Station
GPS
Compass
Telemetry
Servo Actuators
CAN Bus Communication
Mission Planner Configuration
GPS
Parameter	Value
GPS_TYPE2	1
SERIAL4_PROTOCOL	5
SERIAL4_BAUD	115200
CAN Bus
Parameter	Value
CAN_P1_DRIVER	1
CAN_D1_PROTOCOL	1
CAN_P1_BITRATE	1000000
Flight Modes
Mode	Purpose
AUTO	Autonomous Mission Execution
GUIDED	Command Testing
LOITER	Position Hold
RTL	Return to Launch
MANUAL	Ground Validation
Servo Mapping
Output	Function
MAIN OUT 1	Aileron
MAIN OUT 2	Elevator
MAIN OUT 3	Throttle
MAIN OUT 4	Rudder
MAIN OUT 8	Parachute Trigger

Navigation Configuration

GPS Enabled
Compass Calibration
EKF3 Position Estimation
Barometer
Arming Safety Checks
Auto GPS Detection

Features

Autonomous Waypoint Navigation
Mission Planning
Trajectory Generation
Flight Guidance Algorithms
Autonomous Mission Execution
FCU–FADEC CAN Communication
Sensor Integration
Flight Mode Validation
Servo Validation

Mission Planner Integration

Ground Control Station Support
MAVLink Communication
SIL Validation
HIL Validation
Ground Testing
Simulation

The project supports:

MATLAB Simulation
Simulink
ArduPilot SITL
Mission Planner
SIL Connector

ArduPilot SIL Connector

https://fst.aviumtechnologies.com/ardupilot-sil-connector

Repository Structure
Mission-Planning-Guidance-Systems
│
├── Models
├── MATLAB Scripts
├── Mission Planner Files
├── Parameters
├── Documentation
├── Images
├── Results
└── Videos
Results

✔ Successful FCU Integration

✔ CAN Communication Verified

✔ GPS Navigation Verified

✔ Servo Output Validation Completed

✔ Autonomous Mission Execution

✔ SIL Simulation Passed

✔ HIL Validation Completed

✔ Ground Testing Completed

Demo
Mission Planner Simulation
Simulink Integration
Autonomous Waypoint Mission
Flight Mode Validation
FCU–FADEC Communication
