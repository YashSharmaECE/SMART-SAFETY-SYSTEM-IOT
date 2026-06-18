# Smart Safety System with IoT

## Overview
Smart Safety System is an IoT-based intelligent safety solution designed to improve worker safety in hazardous environments such as mines, factories, and industrial workplaces.

This system continuously monitors environmental and health parameters and provides instant alerts during emergency situations.

---

## Features
- 🌡 Real-time Temperature Monitoring
- ☠ Gas Leak Detection
- ❤️ Pulse Rate Monitoring
- 🚨 Emergency Alert System
- 📳 Vibration-Based Direction Guidance
- 📱 Blynk Mobile Notifications
- 📟 LCD Live Status Display
- 🤖 Edge AI Threat Detection

---

## Problem Statement
Workers in mining and industrial environments are exposed to dangerous conditions such as:

- Toxic gas leakage
- Fire hazards
- High temperature
- Worker collapse/fall
- Health emergencies

Manual monitoring is not always reliable, so an automated intelligent safety system is required.

---

## Solution
This project uses ESP32 with multiple sensors to detect unsafe conditions in real time.

When danger is detected, the system:

1. Activates buzzer alerts  
2. Sends mobile notification  
3. Displays emergency message on LCD  
4. Provides escape direction using vibration motors  

---

## Hardware Components
- ESP32
- DHT22 Sensor
- Gas Sensor
- Pulse Sensor
- MPU6050
- LCD I2C Display
- Servo Motors
- Buzzer
- LEDs

---

## Software & Tools
- Arduino IDE
- Blynk IoT Platform
- Embedded C / Arduino C++
- Wokwi Simulator

---

## Working Principle
The system collects data from sensors and processes it using an 8-stage threat detection logic.

Danger conditions include:

- Fire detection
- Gas leakage
- Worker panic
- Fall detection
- Critical emergency situations

Based on sensor data, the system classifies conditions as SAFE or EMERGENCY.

---

## Future Improvements
- GPS Tracking
- GSM Emergency Calling
- Machine Learning Prediction
- Cloud Dashboard Analytics
- Battery Optimization

---

## Author
**Yash Sharma**  
B.Tech ECE Student  
Rustamji Institute of Technology (RJIT)  
VLSI & AI Enthusiast

---
