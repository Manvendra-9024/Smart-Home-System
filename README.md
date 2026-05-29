# Smart Home System

## Overview
A comprehensive IoT-based smart home automation system that enables remote monitoring and control of home devices via a web/mobile interface.

## Tools & Technologies
- **Python** – Backend logic, device control scripts
- **IoT / Arduino** – Sensor reading (temperature, motion, light)
- **Raspberry Pi** – Central hub running the automation server
- **Node.js** – REST API and real-time WebSocket server
- **MySQL** – Device state and event logging
- **Machine Learning** – Predictive automation (e.g., auto-adjust AC based on usage patterns)

## Project Structure
```
smart_home_system/
├── hardware/
│   ├── arduino_sensors.ino
│   └── wiring_diagram.png
├── server/
│   ├── app.js
│   ├── routes/
│   └── models/
├── ml/
│   └── usage_predictor.py
├── scripts/
│   └── device_control.py
├── database/
│   └── schema.sql
└── README.md
```

## Features
- Real-time sensor dashboard (temperature, humidity, motion)
- Remote device control (lights, fans, locks)
- Automated routines with ML-based scheduling
- Alert notifications for anomalies
- MySQL-backed event history

## Setup
```bash
# Arduino: Upload arduino_sensors.ino via Arduino IDE
# Raspberry Pi:
pip install -r requirements.txt
node server/app.js
```
