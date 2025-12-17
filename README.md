# SalihCore-V2.0

SalihCore-V2.0 is a custom STM32-based development board designed for embedded systems prototyping, experimentation, and small-scale product development. The board integrates commonly used peripherals and expansion options while maintaining a compact, robust, and professional hardware design.

The PCB was designed using **Altium Designer** and implemented as a **4-layer board with controlled impedance**, making it suitable for reliable high-speed signals and future scalability.

---

## Key Features

* **STM32 Microcontroller** as the main processing unit
* **USB-C interface** for power and communication
* **Onboard buck converter** for efficient 5 V → 3.3 V power conversion
* **SD card interface** for data logging and storage
* **Motor driver** for basic motor control applications
* **LoRa module headers** for long-range wireless communication expansion
* **GPIO headers** exposing microcontroller pins for external interfacing
* **Push buttons** for user input and control
* **Status LEDs** for power, activity, and debugging indications

---

## Hardware Overview

SalihCore-V2.0 is designed as a general-purpose development platform. The board combines power management, communication interfaces, user I/O, and expansion headers on a single PCB to reduce external wiring and speed up development.

### Power Architecture

* USB-C provides a 5 V input supply
* An onboard buck converter (RT6212AB) efficiently regulates 5 V down to 3.3 V
* 3.3 V rail powers the STM32 and all onboard peripherals

### Communication & Storage

* SD card interface for file storage and data logging
* SD card is connected the mcu via SDIO interface for faster Read/Write compared to SPI
* Dedicated headers for LoRa modules, enabling long-range wireless communication

### Control & I/O

* Integrated motor driver for control applications
* Push buttons for reset or user-defined inputs
* Status LEDs for visual system feedback
* GPIO headers for rapid prototyping and external module integration

---

## PCB Design

* **EDA Tool:** Altium Designer
* **Layer Count:** 4 layers
* **Stack-up:** Designed with controlled impedance

The controlled-impedance stack-up ensures stable operation for high-speed signals and improves overall reliability.

---

## Intended Use Cases

* STM32 firmware development and testing
* Embedded systems learning and experimentation
* Motor control projects
* Data logging applications using SD cards
* Wireless communication projects using LoRa modules

---

## Repository Contents

This repository may include:

* Schematic files
* PCB layout files
* BOM
* Manufacturing outputs (Gerbers, drill files)
* Documentation and notes

> Firmware examples and application code may be added in future revisions.

---



## Author
Designed and developed by Salih.

Designed and developed by **Salih**.
