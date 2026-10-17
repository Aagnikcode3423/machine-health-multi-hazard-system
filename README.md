# Machine Health and Multi-Hazard Detection System

An ESP32-based engineering project focused on machine health monitoring and multi-hazard detection, with scope for real-time monitoring, fault alerts, and future predictive maintenance integration.

## Overview

This project explores the integration of embedded systems, sensors, and software to monitor machine operating conditions and detect potentially hazardous situations.

The long-term goal is to develop a system that combines machine health monitoring with intelligent fault detection and a digital twin for industrial applications.

## Key Objectives

- Monitor relevant machine operating parameters using sensors.
- Detect selected environmental and machine-related hazards.
- Generate alerts when configured conditions are triggered.
- Explore real-time data visualization and remote monitoring.
- Establish a foundation for future digital twin and predictive maintenance capabilities.

## System Architecture

**Sensors → ESP32 → Data Processing → Alerts and Monitoring Interface**

The exact architecture depends on the implemented hardware and software configuration.

## Technologies

- **Microcontroller:** ESP32
- **Programming:** Embedded C/C++ 
- **Sensors:** ## Sensors and Hardware

- **ESP32:** Main microcontroller for sensor data acquisition and processing.
- **PIR Sensor:** Detects movement of warm bodies within its detection range.
- **IR Sensor:** Detects nearby objects using infrared sensing.
- **Flame Sensor:** Detects flame-related infrared radiation.
- **MQ-2 Gas Sensor:** Detects smoke and certain combustible gases.
- **MPU6050:** Measures acceleration and angular velocity for motion and vibration-related monitoring.
- **Temperature and Humidity Sensor:** Monitors ambient environmental conditions.
- **Buzzer:** Provides an audible alert when configured hazard conditions are detected.


## Project Status

The initial prototype has been developed. Further work will focus on documenting the implementation, improving system integration, and exploring digital twin and predictive maintenance capabilities.

## Future Scope

- Develop a digital twin with live machine parameters.
- Explore machine-learning-based predictive maintenance.
- Improve fault detection and alert logic.
- Investigate industrial monitoring and safety applications.

## Author

Mechanical Engineering Student  
National Institute of Technology Durgapur

---

*This project is an ongoing step toward integrating embedded systems, machine monitoring, and intelligent predictive maintenance.*
