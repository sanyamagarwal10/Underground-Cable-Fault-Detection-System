# Underground Cable Fault Detection System

## 📑 Overview
This project presents a cost-effective and scalable solution for detecting and locating faults in underground power cables using an ESP32 microcontroller. With the increasing adoption of underground cabling in urban and industrial settings, identifying faults quickly and accurately is critical for ensuring reliable power distribution and minimizing downtime.

This system leverages the principle of Ohm's Law and voltage drop analysis to detect and localize cable faults. Additional features such as LCD display, GSM alert system, and remote monitoring make it ideal for real-time smart grid applications.

## 🎯 Objectives
-- Detect underground cable faults accurately using ESP32
-- Display fault information (type, distance, phase) on a 16x2 LCD
-- Send SMS alerts to maintenance personnel using GSM
-- Provide cost-efficient, scalable, and energy-efficient fault detection
-- Enable integration with future smart grid and IoT platforms

## 🧠 Working Principle
Voltage and current are continuously monitored across cable segments simulated using resistors.
On fault detection, the ESP32 microcontroller calculates the distance to the fault using the voltage drop.
The system classifies the fault (short circuit, open circuit, or earth fault).
Fault data is displayed on an LCD and transmitted via GSM.

## 🔧 Components Used
Component	Description
ESP32 Microcontroller	Central controller
16x2 LCD with I2C Module	Fault data display
Voltage & Current Sensors	Input data for fault detection
1-Channel Relay Module	Phase control
GSM Module	SMS alert system
Resistors	Cable segment simulation
Push Buttons	Fault simulation switches
Arduino IDE	Development environment

## 🔩 Tools Required
Soldering Iron & Electrical Solder
Wire Stripper
Zero PCB
Power Supply Unit

## 🧪 Experimental Setup
Simulated 3-phase system using resistors and switches
Fault injected at specific points
System monitored fault type and location
LCD displayed real-time results
GSM sent SMS alerts upon fault detection

## 📊 Results & Performance
Accurate detection of short-circuit and earth faults
Real-time monitoring with low power consumption
Quick response and notification via SMS
Modular and expandable system suitable for smart grid integration

## ⚙️ Methodology
System Initialization: Sensor calibration and voltage baseline setup.
Data Acquisition: Real-time voltage and current reading via ADC.
Fault Detection: Threshold-based anomaly recognition.
Fault Localization: Voltage drop used to estimate distance.
Notification: Fault displayed on LCD and sent via GSM.

## 🌍 Environmental & Societal Benefits
Reduces unnecessary excavation and environmental disruption
Enhances worker and public safety
Minimizes power outage time
Supports remote and rural electrification

## 🔮 Future Enhancements
Incorporate capacitive/impedance-based sensing for open-circuit detection
Cloud-based data logging and visualization
Integration with LoRa/Wi-Fi for enhanced connectivity
Machine learning-based predictive maintenance
