# KSW01 Smartwatch

![KSW01](images/ksw01.png)

## Overview

The **KSW01** is a modern round smartwatch designed for everyday fitness, health monitoring, and smart connectivity. Built around **Zephyr RTOS**, it combines a premium minimalist design with efficient embedded performance.

With its 43 mm circular case, vibrant AMOLED display, health sensors, and magnetic charging system, the KSW01 is designed as an open and customizable smartwatch platform.

---

## Key Features

### Display

* 1.43" AMOLED Display
* Resolution: **466 × 466**
* Custom watch faces

### Software

* Powered by **Zephyr RTOS**
* Fast boot times
* Low-power operation
* Modular firmware architecture
* OTA firmware update support (planned)

### Health & Fitness

* Heart Rate Monitoring
* Blood Oxygen (SpO₂) Tracking
* Sleep Monitoring
* Step Counter
* Calorie Tracking
* Workout Modes

### Connectivity

* Bluetooth Low Energy (BLE)
* Smartphone Notifications
* Call Alerts
* Message Alerts
* Music Control

### Battery

* Magnetic 2-Pin Charging System
* USB-A Charging Cable
* Fast Charging Support
* Optimized Zephyr Power Management

---

## Hardware Specifications

| Component        | Specification           |
| ---------------- | ----------------------- |
| Model            | KSW01                   |
| Case Diameter    | 43 mm                   |
| Display          | AMOLED                  |
| Resolution       | 466 × 466               |
| Operating System | Zephyr RTOS             |
| Charging         | Magnetic 2-Pin          |
| Connectivity     | Bluetooth LE            |
| Sensors          | HR, SpO₂, Accelerometer |
| Strap Type       | Quick Release           |
| Water Resistance | TBD                     |
| Battery Capacity | TBD                     |

---

## Design

### Front

* Edge-to-edge circular display
* Minimal bezel design
* Dual side buttons
* Customizable watch faces

### Rear

* Optical sensor array
* Magnetic charging contacts
* Regulatory markings
* Durable composite backplate

---

## Charging System

The KSW01 uses a dedicated magnetic charging puck that aligns automatically with the charging contacts on the back of the watch.

### Features

* Strong magnetic attachment
* Reverse polarity protection
* Overvoltage protection
* Stable charging current
* Compact travel-friendly design

---

## Watch Face Example

Features shown on the default watch face:

* Time and date
* Step count
* Calories burned
* Heart rate
* AMOLED optimized colors

---

## Development

### Firmware Stack

```text
Application Layer
│
├── UI Framework
├── Health Services
├── BLE Services
├── Sensor Manager
│
Zephyr RTOS
│
Hardware Drivers
```

### Planned SDK Support

* Zephyr Build System
* Photo-based Dial Development
* BLE Application Development

---

## Roadmap

### Version 1.0

* Core smartwatch functionality
* Health tracking
* Notifications
* Magnetic charging

### Version 1.1

* OTA Updates
* Additional watch faces
* Enhanced fitness tracking

---

## Package Contents

* KSW01 Smartwatch
* Magnetic Charging Cable
* Quick Start Guide
* Warranty Card

---

## Status

🚧 Prototype Development Phase

The KSW01 is currently in active development. Specifications and features may change before final production.

---

## About Kairosmart

Kairosmart is a Shenzhen-based wearable technology startup focused on creating efficient smart devices powered by modern embedded software platforms.

---

## License

Copyright © 2026 Kairosmart

All rights reserved.
