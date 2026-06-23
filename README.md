<div align="center">

# RP2040 BYH DevBoard

### A compact, beginner-friendly RP2040 development board designed for prototyping, learning, and embedded projects.

<img src="https://github.com/user-attachments/assets/d69686d8-a1bf-4bce-9087-ded401f39412" width="650">

<br>

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![MCU](https://img.shields.io/badge/MCU-RP2040-blue?style=for-the-badge)
![Flash](https://img.shields.io/badge/Flash-16MB-green?style=for-the-badge)
![USB](https://img.shields.io/badge/USB-Type--C-orange?style=for-the-badge)

</div>

---

# Overview

The **BYH DevBoard** is a custom development board built around the **Raspberry Pi RP2040** microcontroller. Designed with simplicity and accessibility in mind, it exposes the RP2040's GPIO pins through standard **2.54 mm headers**, making it ideal for breadboarding, prototyping, and embedded development.

The board features **16 MB of SPI Flash**, USB-C connectivity for programming and power, onboard power regulation, and all of the essential support circuitry required by the RP2040.

---

# Features

* Raspberry Pi RP2040 Microcontroller
* Dual-core ARM Cortex-M0+ @ 133 MHz
* 16 MB SPI Flash Storage
* USB Type-C Interface
* 2.54 mm Breakout Headers
* Onboard 3.3 V LDO Regulator
* Compact Surface-Mount Design
* Breadboard Friendly
* Open Hardware Design

---

# Hardware Specifications

| Component         | Specification   |
| ----------------- | --------------- |
| Microcontroller   | RP2040          |
| Flash Memory      | 16 MB SPI Flash |
| USB               | USB Type-C      |
| Operating Voltage | 3.3 V           |
| Crystal           | 12 MHz          |
| GPIO Access       | 2.54 mm Headers |
| PCB               | Custom FR4 PCB  |

---

# PCB Design

### Schematic

<p align="center">

<img src="https://github.com/user-attachments/assets/802d1894-c57f-45f3-b99f-609b152303e8" width="90%">

</p>

### PCB Layout

<p align="center">

<img src="https://github.com/user-attachments/assets/8fc96c75-4aee-4737-8dd9-7d2ba9697868" width="90%">

</p>

---

# Components & Ordering

<p align="center">

<img src="https://github.com/user-attachments/assets/9c26cbcf-7f69-4021-bf5e-784d47172d70" width="45%">
<img src="https://github.com/user-attachments/assets/1b64459d-8ee1-4fe6-a5db-73962a49ad77" width="45%">

<br>

<img src="https://github.com/user-attachments/assets/f083975f-33fe-4686-83c5-271cefb0e37b" width="45%">
<img src="https://github.com/user-attachments/assets/a2b7b8d3-c566-420d-9c73-ed5e59eadc6f" width="45%">

</p>

---

# Bill of Materials

## Core Components

| Component            | Qty | Description          |
| -------------------- | --: | -------------------- |
| Custom PCB           |   5 | 1.6 mm FR4, HASL     |
| RP2040 MCU           |   1 | Raspberry Pi RP2040  |
| 16 MB SPI Flash      |   1 | Winbond W25Q16JVZPIQ |
| 3.3 V LDO            |   3 | MCP1700T-3302E       |
| 12 MHz Crystal       |   3 | YSX321SL             |
| USB Type-C Connector |   3 | 16-Pin SMD           |
| 2.54 mm Headers      |   3 | 1×40 SMT             |
| Tactile Switch       |   3 | Boot & Reset         |

---

## Passive Components (0402)

| Component         | Qty |
| ----------------- | --: |
| 100 nF Capacitors |  45 |
| 1 µF Capacitors   |  20 |
| 10 µF Capacitors  |  10 |
| 33 pF Capacitors  |  20 |
| 27 Ω Resistors    |  20 |
| 5.1 kΩ Resistors  |  20 |
| 1 kΩ Resistors    |  20 |
| 10 kΩ Resistors   |  20 |

---

# Estimated Cost

| Category                 |          Cost |
| ------------------------ | ------------: |
| Core Components          | **₹2,290.00** |
| Passive Components       |   **₹224.85** |
| **Total Estimated Cost** | **₹2,514.85** |

---

# Pinout

The BYH DevBoard exposes nearly every RP2040 GPIO pin through standard **2.54 mm headers**, making it compatible with breadboards, jumper wires, sensors, displays, and common development modules.

---

# Why I Built It

Commercial RP2040 development boards are excellent, but I wanted to understand what goes into designing one from scratch.

This project gave me hands-on experience with:

* RP2040 reference design
* High-speed USB routing
* Power supply design
* PCB layout best practices
* Component sourcing
* Manufacturing preparation
* Hardware documentation

---

# Future Improvements

* USB ESD Protection
* Power LED
* User Programmable LED
* SWD Debug Header
* Castellated Edge Version
* Battery Support

---

<div align="center">

### Designed from scratch to learn hardware by building it.

</div>
