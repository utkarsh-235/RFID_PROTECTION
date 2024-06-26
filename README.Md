# RFID Door Lock Protection System

## Overview
This project is a RFID door lock protection system designed to secure access to a particular area or building using RFID cards or tags. The system includes hardware components such as an RFID reader, microcontroller, and an electric door lock, as well as software components for authentication and access control.

## Features
- Secure access control using RFID cards or tags
- Easy integration with existing door lock systems
- Configurable access privileges for different users
- Event logging for access attempts
- Alarm system for unauthorized access attempts

## Hardware Requirements
- Arduino or compatible microcontroller board
- RFID reader module
- Electric door lock mechanism
- Relay module
- Power supply
- LEDs and buzzer for feedback and alarm

## Software Requirements
- Arduino IDE or compatible development environment
- RFID library for Arduino
- Custom software for authentication and access control

## Installation
1. Connect the RFID reader module to the microcontroller board according to the provided schematics.
2. Connect the electric door lock mechanism via the relay module.
3. Upload the provided Arduino sketch to the microcontroller board.
4. Install the required libraries in your Arduino IDE.
5. Configure the access control settings and RFID card IDs in the Arduino sketch.
6. Power on the system and test the functionality.

## Usage
1. Present a registered RFID card or tag to the RFID reader.
2. The system will authenticate the card and unlock the door if access is granted.
3. Access attempts are logged for review.
4. Unauthorized access attempts trigger the alarm system.

