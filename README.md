DeepTech Nucleo-F767ZI Interface Board

This repository contains the hardware design files for a custom expansion shield for the ST Nucleo-F767ZI.
The board provides clean, robust, and robotics-oriented breakouts for ESCs, sensors, SPI modules, I²C devices, and CAN communication, making it ideal for AGV, ROV, UAV, and general embedded-systems development.

🧩 Features
🔌 Nucleo-144 Compatible Shield

Fully aligned with the official NUCLEO-F767ZI pinout

Direct access to all major GPIO blocks

Large ground plane for electrical stability

⚡ ESC Output Bank

12× ESC/PWM headers

Each header includes: GND, VCC, SIG

Timer pins routed cleanly for stable PWM generation

🧭 I²C Sensor Ports

Dual I²C headers

Includes 10kΩ SDA/SCL pull-ups

Optimized trace length matching for reliability

🚀 SPI Expansion Ports

Multiple SPI breakouts

Each provides: GND, VCC, SCK, MISO, MOSI, CS

Suitable for IMUs, radios, flash memory, etc.

🚐 CAN Bus Interface

TCAN transceiver footprint

CANH / CANL screw-terminal output

On-board termination resistor

🛠 Mechanical & Layout

3.2 mm mounting holes in all corners

Clean blue PCB design with DeepTech branding

Compatible with KiCad 7/8/9

3D model files included
