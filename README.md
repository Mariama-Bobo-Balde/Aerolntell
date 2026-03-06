# AeroIntell

AeroIntell is an intelligent aircraft maintenance system designed to improve aircraft reliability through data monitoring and predictive maintenance.

The project combines embedded systems, data analysis, and backend architecture to detect abnormal behavior in aircraft components such as engines.

## Project Goals

- Monitor aircraft operational data
- Detect anomalies in temperature and vibration signals
- Support predictive maintenance decisions
- Improve reliability and reduce unexpected failures

## System Architecture

AeroIntell is built around three main components:

### Embedded Node
A hardware module that collects sensor data such as:
- temperature
- vibration

The data is stored locally and transmitted when a connection is available.

### Backend / Data Processing
A backend system that stores and analyzes data to detect abnormal patterns and maintenance risks.

### Control Center
A web interface that allows engineers to:
- monitor aircraft status
- visualize alerts
- track maintenance information

## Technologies

- Embedded Systems (ESP32 / Arduino)
- Python
- SQL
- Data analysis
- Web interface

## Status

Project in early development phase.
