# Intelligent Smart Precision Agriculture System

An IoT and Machine Learning based hydroponic agriculture system designed for real-time environmental monitoring and automated irrigation. The system integrates sensor networks, cloud infrastructure, and time-series machine learning to optimize water usage and improve crop yield in controlled farming environments.

---

## Demonstration

https://github.com/user-attachments/assets/f51d34ea-2663-405d-8a9b-a75b516388c0

---

## Overview

The Intelligent Smart Precision Agriculture System collects environmental data using multiple sensors connected to an ESP32 microcontroller. Sensor readings are transmitted to cloud platforms for storage and visualization. A Long Short-Term Memory (LSTM) model processes time-series data to predict irrigation requirements and automate watering through a relay-controlled pump.

This approach enables data-driven hydroponic farming, reducing water consumption while maintaining optimal crop growth conditions.

---

## Key Features

- Real-time monitoring of environmental parameters including pH, soil moisture, temperature, humidity, and light intensity
- Automated irrigation triggered by machine learning predictions
- Cloud-based data storage using Firebase Realtime Database
- Sensor data visualization through ThingSpeak dashboards
- Manual monitoring and control through web or mobile interfaces
- Time-series prediction using an LSTM neural network

---

## System Architecture

![System Architecture](https://github.com/user-attachments/assets/11563928-8b6d-4af4-b9dc-f745394707ad)

---

## Hardware Components

| Component | Description |
|----------|-------------|
| ESP32 | Microcontroller responsible for sensor integration and network communication |
| DHT11 | Temperature and humidity sensor |
| Soil Moisture Sensor | Measures water content in the growing medium |
| LDR | Detects ambient light intensity |
| pH Sensor | Measures acidity/alkalinity of nutrient solution |
| Relay Module | Controls irrigation pump |
| Water Pump | Automates irrigation |

---

## Software Stack

| Layer | Technology |
|------|-------------|
| Firmware | Arduino Framework (C++) |
| Microcontroller | ESP32 |
| Cloud Infrastructure | Firebase Realtime Database |
| Data Visualization | ThingSpeak |
| Machine Learning | TensorFlow / Keras |
| ML Model | Long Short-Term Memory (LSTM) |
| Programming Languages | C++, Python |

---

## Repository Structure
