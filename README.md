# StabiSense : A Self-Calibrating IMU-Based Micro-Scale Stabilization System with Real-Time Adaptive Control
🕒May 24,2026
---
> Real-time seismic monitoring and adaptive calibration for vibration-sensitive environments.
---

## Acknowledgements
This project was developed as part of IEEE MYOSA 5.0 with support from Mar Baselios Institute of Technology and Science.
We would also like to thank our faculty mentor for his valuable guidance and support during the development of StabiSense.

---

## Overview
StabiSense is a high accurate seismic detection and adaptively calibrated system designed to monitor vibrations in wafer fabrication environments. This system continuously collects real-time motion data along with changes in the environment from multiple integrated sensors connected to the MYOSA ESP32 platform.

The use of IMU-based motion detection with environmental telemetry and LSTM-based time series analysis enables the StabiSense to identify, classify and differentiate between normal types of vibration and seismic related vibrations before determining an event has occurred. This also provides live telemetry visualization of the data and allows storing the recorded data for future analysis and replay of the recorded data through a web-based dashboard.

### Key Features
- Real-time seismic and vibration monitoring
- LSTM-based seismic pattern detection
- Live telemetry dashboard visualization of data using waveform graphs
- Event logging and replay of recorded events
- 3D visualization of motion and orientation
- Serial and BLE based transmission of data

---

## Demo/Examples

### Images

### Videos

---

## Features(Detailed)

### 1. Real-Time Seismic Detection
The MPU6050’s accelerometer and gyroscope continuously collect the acceleration and gyroscope values from all three axes to detect vibrations, disturbances from movement, and seismic events in real-time.

### 2. Environmental Monitoring
Using the BMP180, it monitors the atmospheric pressure, temperature and altitude of the environment.

### 3. AI- Based Vibration Classification
An LSTM approach to time series analysis, to learn the characteristics of seismic waveforms in order to separate actual seismic activity from normal vibration or random disturbance vibration. The use of synthetic datasets during training improves detection accuracy, and event classification.

### 4. Telemetry Dashboard
Provides real-time telemetry of sensor measurements for vibration, pressure, and motion data through a web-based dashboard.

### 5. Event Recording and Replaying
Captures the telemetry data from the sensors in real time throughout the occurrence of a vibration event. The data can be reviewed later for analysis and recalibration.

### 6. 3D Motion Visualization
A real-time, 3D motion model of the device to visually illustrate the motion of the device by way of roll and pitch data produced by the IMU sensors

---

## Usage Instructions

---

## Tech Stack

---

## Requirements / Installation

---

## File Structure

