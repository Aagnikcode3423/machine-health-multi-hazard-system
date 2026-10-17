# System Architecture

## Project Overview

The Machine Health and Multi-Hazard Detection System uses an ESP32 microcontroller to collect sensor readings, classify configured hazard conditions, and present monitoring information through a locally hosted web dashboard.

## System Workflow

1. Sensors collect environmental, motion, and machine-related data.
2. The ESP32 reads and processes the sensor signals.
3. Configured thresholds classify readings as SAFE, WARNING, or CRITICAL.
4. The ESP32 updates the system status and controls the connected indicator LEDs and buzzer.
5. A web dashboard displays sensor readings and overall hazard status over the ESP32's local Wi-Fi network.

## Sensor Modules

- DHT11 — temperature and relative humidity
- MQ-2 — gas and smoke-related sensor readings
- PIR — motion detection
- Flame sensor — flame detection
- MPU6050 — acceleration-based motion and vibration estimation

## Monitoring Interface

The ESP32 operates as a Wi-Fi access point and hosts a web server. A connected device can open the dashboard using the ESP32's local IP address.

## Limitations

Sensor thresholds require appropriate testing and calibration for the intended application. The prototype is an educational monitoring system and should not be treated as a certified industrial safety system.

## Future Development

- Improve sensor calibration and fault detection.
- Develop a digital twin with live operating parameters.
- Explore data-driven predictive maintenance.
- Improve system testing and technical documentation.
