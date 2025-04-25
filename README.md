# Serial Converter – PCB Design (KiCad 9)

This repository contains the design files for a **Serial Converter PCB** created using **KiCad 9**. The board provides a simple and effective solution for converting serial communication levels—ideal for embedded systems, microcontroller interfacing, or general-purpose serial communication debugging.

## Features

- Designed in **KiCad 9**
- Converts **TTL ↔ RS232** (or USB, based on configuration)
- Compact and modular PCB layout
- Includes schematics, PCB layout, and ready-to-manufacture Gerber files
- Open-source hardware for learning and development

## Repository Contents

- `*.kicad_pcb` – PCB layout file
- `*.sch` – Schematic diagram (See: [Serial_Converter_Schematic.pdf](./Serial_Converter_Schematic.pdf))
- `*.bom` – Bill of Materials
- `*.gerber/` – Production-ready Gerber files
- `README.md` – Project overview and documentation

## Schematic Preview

![Schematic Thumbnail](./Serial_Converter_Schematic.pdf)  
*For a detailed view, open the PDF version directly.*

## Tools Required

- **KiCad 9** (or compatible newer versions)
- A PCB fabrication service (e.g., JLCPCB, OSH Park)
- Basic soldering tools and components (listed in BOM)

## Usage

Use this board as a bridge for serial communication between TTL logic devices (like Arduinos, ESP32, STM32, etc.) and RS232 or USB-based interfaces. Modify the schematic to fit your voltage or connector requirements.

## License

This project is licensed under the **MIT License**.
---

Built with passion and precision using **KiCad 9**.

