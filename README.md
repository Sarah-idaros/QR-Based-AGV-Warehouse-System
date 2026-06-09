# QR-Based-AGV-Warehouse-System
# QR-Based-AGV-Warehouse-System

## Physical Prototype

![AGV Prototype](AGV_Front.jpg)

## System Architecture

![System Architecture](System_Architecture.png)

## Wiring Diagram

![Wiring Diagram](Wiring_Diagram.png)

## Navigation Layout

![Navigation Layout](QR_Navigation_Map.png)

## Mobile Application

![Flutter Home](Flutter_Home.png)

## Overview

This project presents a QR-Based Autonomous Guided Vehicle (AGV) developed for indoor warehouse logistics and material transportation. The system uses QR code markers placed at warehouse junctions to perform navigation and routing without requiring expensive localization technologies.

The AGV is capable of transporting boxes between a loading station and multiple delivery stations while supporting forward delivery, return-to-home, and reverse pickup operations.

The project was developed using ESP32, QR code navigation, wireless communication, obstacle detection, and a Flutter-based monitoring application.

## Key Features

- QR-Based Navigation
- Autonomous Warehouse Transportation
- Multi-Station Routing
- ESP32-WROOM-32D Controller
- HC-SR04 Obstacle Detection
- PIR Cargo Detection
- BTS7960 Motor Drivers
- Wi-Fi Communication
- Flutter Monitoring Application
- Forward Mode
- Return Mode
- Reverse Mode

## Hardware Components

- ESP32-WROOM-32D
- GM67 QR Scanner
- HC-SR04 Ultrasonic Sensor
- PIR Motion Sensor
- BTS7960 Motor Drivers
- 12V DC Motors
- 12V Battery

## Technologies

- Embedded C/C++
- Arduino IDE
- ESP32
- Wi-Fi Communication
- QR Navigation
- State Machine Logic
- Flutter
