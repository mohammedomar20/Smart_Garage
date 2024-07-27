Smart Garage 
This repository contains the code and schematics for an Arduino-based smart garage system. The system automates parking management, monitors temperature, and adjusts lighting based on day/night conditions.

Features:
Automated gate control using servo motor and infrared sensors
Real-time parking slot monitoring with LDRs
Temperature monitoring with a fire alarm feature
Day/night detection for lighting control
LCD display for user interface

Hardware Components:
Arduino Uno
Infrared sensors (IR1, IR2)
Light-dependent resistors (LDRs)
Temperature sensor (A5)
Servo motor
Buzzer
LEDs
LCD display

Software Techniques:
C++ programming for real-time data acquisition and processing
Integration of multiple sensors and actuators
Implementation of control logic for automated gate, lighting, and alarm systems
LCD display management for user interface

Usage:
Assemble the hardware components as per the schematic.
Power on the system.
The LCD will display real-time information about parking slots, temperature, and welcome messages.
The gate will automatically open and close based on the IR sensor readings.
The LEDs will turn on/off based on the LDR readings indicating day/night conditions.
The buzzer and blinking LED will activate if the temperature exceeds a safe threshold.
