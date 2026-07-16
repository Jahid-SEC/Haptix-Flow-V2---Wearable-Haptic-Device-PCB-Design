# Haptix Flow V2 – Wearable Haptic Device PCB Design

> Commercial wearable hardware designed for **Haptix Labs**.

## Overview

**Haptix Flow V2** is a commercial wearable haptic device developed for **Haptix Labs** that delivers bilateral haptic stimulation to support stress reduction, improved focus, and cognitive readiness through synchronized left-right vibration. Designed as a compact, low-power wearable, it combines Bluetooth Low Energy (BLE), motion sensing, and precision haptic feedback in a portable form factor.

My contribution to this project included the complete **hardware architecture, schematic design, RF integration, and 4-layer PCB design**, with a focus on signal integrity, power efficiency, manufacturability, and reliable wireless performance.


As part of this commercial project for **Haptix Labs**, my responsibilities included:

* Hardware Architecture Design
* Schematic Design
* 4-Layer PCB Design
* RF Layout and Antenna Integration
* Power Distribution and Signal Integrity Optimization
* Manufacturing-Ready PCB Preparation

---

## Features

* Nordic nRF52833 Bluetooth Low Energy (BLE) MCU
* Precision haptic feedback using DRV2605 LRA Driver
* LRA vibration motor support
* USB Type-C charging interface
* Single-cell 3.7 V Li-Po battery operation
* On-board battery charging and power management
* External 64 Mbit SPI Flash memory
* 6-axis IMU for motion sensing
* Compact wearable PCB design
* Low-power hardware architecture
* SWD programming and debugging interface
* ESD, TVS, and reverse-polarity protection
* RF optimized BLE antenna layout
* Manufacturing-ready 4-layer PCB

---

## Applications

* Wearable Technology
* Wellness Devices
* Haptic Feedback Systems
* Human-Computer Interaction
* Motion Tracking
* Consumer Electronics
* BLE Embedded Systems

---

# Hardware Architecture

| Component          | Description                    |
| ------------------ | ------------------------------ |
| MCU                | Nordic nRF52833                |
| Wireless           | Bluetooth Low Energy (BLE)     |
| Haptic Driver      | DRV2605                        |
| Vibration Motor    | Linear Resonant Actuator (LRA) |
| Motion Sensor      | LSM6DSOXTR 6-Axis IMU          |
| External Flash     | Winbond W25Q64JVSSIQ           |
| Battery Charger    | IP5306                         |
| Voltage Regulator  | ME6217C33M5G (3.3 V)           |
| Charging Interface | USB Type-C                     |
| Programming        | SWD Test Pads                  |
| Battery            | Single-cell 3.7 V Li-Po        |

---

# PCB Design Highlights

* 4-Layer PCB Architecture
* Compact wearable form factor (25 × 35 mm)
* Controlled impedance routing
* 90 Ω differential impedance for high-speed differential signals
* 50 Ω RF transmission line for BLE antenna
* Dedicated ground and power planes
* RF antenna matching network
* Ground keep-out region beneath the chip antenna
* Optimized RF trace routing
* Power integrity optimization
* Signal integrity optimization
* Design for Manufacturability (DFM)

---

# PCB Stack-up

| Layer   | Description        |
| ------- | ------------------ |
| Layer 1 | Signal             |
| Layer 2 | Solid Ground Plane |
| Layer 3 | Power Plane        |
| Layer 4 | Signal             |

---

# Protection Features

* ESD Protection
* TVS Diode Protection
* Reverse-Polarity Protection
* Stable 3.3 V Power Regulation

---

# RF Design Considerations

Reliable BLE performance requires careful RF layout. The PCB was designed with:

* Chip antenna integration
* RF impedance matching network
* 50 Ω controlled impedance RF trace
* Ground keep-out underneath the antenna
* Optimized RF routing to minimize signal loss

---

# Power Management

The power subsystem was designed for battery-powered wearable operation.

* Single-cell 3.7 V Li-Po battery
* USB Type-C charging
* IP5306 battery charging and power management
* 3.3 V regulated power rail
* Low-power hardware architecture

---

# Development & Debugging

* SWD programming interface via test pads
* Reset button
* GPIO button for user interaction
* Manufacturing test access points


# My Contribution

This project was completed as a commercial hardware design for **Haptix Labs**.

Responsibilities included:

* Hardware Architecture
* Schematic Design
* Component Selection
* Power Tree Design
* BLE RF Layout
* Antenna Matching Network
* PCB Layout
* Controlled Impedance Routing
* Design Rule Verification (DRC)
* Manufacturing File Generation

---

# Design Notes

This repository is intended to showcase the hardware design work completed for this project. Proprietary design files, schematics, firmware, and manufacturing data are not included due to commercial confidentiality.

---

# Technologies

* Altium Designer
* Nordic nRF52833
* Bluetooth Low Energy (BLE)
* USB Type-C
* DRV2605
* LSM6DSOXTR
* Winbond W25Q64
* IP5306
* 4-Layer PCB
* Controlled Impedance Routing
* RF PCB Design
* Embedded Hardware Design

---

# Disclaimer

This repository is provided for portfolio and documentation purposes only. Certain design files and implementation details are intentionally omitted to respect the intellectual property and confidentiality requirements of the commercial project developed for Haptix Labs.
