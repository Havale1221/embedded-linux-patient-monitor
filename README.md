# embedded-linux-patient-monitor
Patient Health Monitoring Dashboard using Embedded Linux, ESP32, Python, and Flask for real-time SpO₂, pulse rate, temperature monitoring, graphs, and alerts.

1)PROJECT OVERVIEW

The Patient Health Monitoring Dashboard Using Embedded Linux is a project designed to measure and display patient health parameters using sensors, a microcontroller, and a Linux-based monitoring system.

2)The project can measure three main parameters:

SpO₂: Blood oxygen saturation, displayed as a percentage.

Pulse rate: Heartbeats per minute (BPM).

An ESP32 collects readings from the sensors and sends them to a computer running Ubuntu/Linux. A Python application processes the data and a web dashboard displays the readings, graphs, and alerts.

The dashboard can run locally, so internet access is not required when the hardware and software are configured for USB serial communication.

3) Project objectives
   
Develop a patient health monitoring dashboard.

Interface health sensors with the ESP32.

Display sensor readings in real time.

Visualize readings using graphs and gauges.

Generate configurable warnings when readings cross selected thresholds.

Store historical readings for later analysis.

Learned Embedded Linux, Python, sensor interfacing, and web development.


4)Patient Health Monitoring Dashboard

The Patient Health Monitoring Dashboard is a web-based application developed using Python Flask, HTML, CSS, and JavaScript.

It provides a simple and responsive interface for displaying patient health parameters, including oxygen saturation (SpO₂) and pulse rate (BPM).

The dashboard presents these readings using circular gauges and graphical charts, making the information easy to understand.


<img width="1090" height="793" alt="image" src="https://github.com/user-attachments/assets/0d1cc380-9b5a-4959-bf5e-9b0f4291f8d9" />

Note: This project currently uses demonstration readings. It does not collect real patient data or connect to medical sensors.


