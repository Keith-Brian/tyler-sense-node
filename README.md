# TylerSense

**TylerSense** is a GSM-powered, sensor-based home automation and environmental monitoring system built in loving memory of my dear friend, Tyler.  
Designed to provide real-time data sensing, control, and remote communication for smart home and rural deployments.

![License](https://img.shields.io/github/license/your-username/TylerSense)
![Platform](https://img.shields.io/badge/platform-ESP32-blue)
![Status](https://img.shields.io/badge/status-In_Development-orange)

---

## 🧠 Project Overview

TylerSense integrates multiple environmental and motion sensors with an ESP32 microcontroller, SIM800L GSM module, and relay actuators to automate and monitor living spaces.  
It’s designed for offline and remote areas, making it suitable for homes, farms, and legacy buildings.

---

## 🔧 Features

- 📶 **GSM Connectivity** via SIM800L for remote communication
- 🌡️ **Environmental Monitoring** (Temperature, Humidity, Air Quality)
- 🕹️ **Actuator Control** (2 Relays for lights, fans, or other appliances)
- 📊 **Data Logging** to SD card and/or cloud
- 🌞 **Light Monitoring** using BH1750
- 💨 **Particulate Matter Monitoring** using PMS5003
- 🧠 **Modular Design** – easily expandable via I2C/SPI headers
- 🔋 **Low Power Ready** – ideal for solar-powered use cases

---

## 📦 Hardware Components

| Component       | Description                       |
|----------------|-----------------------------------|
| ESP32 DevKit    | Main microcontroller (Wi-Fi + BT) |
| SIM800L Core    | GSM module for SMS/HTTP           |
| ULN2003A        | Relay driver IC                   |
| DHT22           | Temp & Humidity sensor            |
| MQ-7            | Carbon Monoxide sensor            |
| PMS5003         | Particulate matter sensor         |
| BH1750          | Light intensity sensor            |
| Micro SD Module | Data logging                      |
| LM2596S         | 5V Buck Converter                 |
| 5V Relays       | Actuator control                  |

---

## 📐 Schematic

You can find the complete schematic [here](./Tyler-Sense.pdf).

---

## 📁 Folder Structure

