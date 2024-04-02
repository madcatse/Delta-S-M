# Delta-S-M Ver.1.0 Gerber Files

![Delta-S-M Logo](https://example.com/logo.png)

Welcome to the first release of Gerber files for Delta-S-M Ver.1.0! This repository contains the manufacturing files necessary to produce the Delta-S-M Ver.1.0 board.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Cable pinout difference](#cable-pinout-difference)
- [Making SCART cable](#making-scart-cable)
- [License](#license)

## Introduction
Основной задачей данного проекта я поставил создание наиболее близкого к оригиналу клона персонального восьмибитного компьютера "Дельта-С", который в свою очередь является клоном ZX Spectrum 48K. Выбор модели был обусловлен давней мечтой об "улучшении" оригинальной машины, которой я обладаю с 1991 года. В процессе работы цель проекта несколько раз корректировалась и вместо точной копии стала некоторой "вариацией" на тему оригинала, с небольшими корректировками.

## Features
- High-performance microcontroller
- Multiple digital and analog I/O options
- Onboard peripherals such as LEDs, buttons, and connectors
- Expandable with additional modules or shields
- Compact form factor for easy integration

## Getting Started
To get started with Delta-S-M Ver.1.0, follow these steps:
1. Clone or download this repository.
2. Open the Gerber files in your preferred PCB manufacturing software.
3. Verify the design and make any necessary adjustments.
4. Generate the necessary manufacturing files (e.g., drill files, copper layers).
5. Submit the generated files to your preferred PCB manufacturer.
6. Review the manufacturer's guidelines and requirements for PCB production.
7. Proceed with the manufacturing process.
8. Once manufactured, assemble the components onto the PCB following the provided bill of materials (BOM).
9. Power up the Delta-S-M Ver.1.0 board and start exploring its capabilities!

## Folder Structure
The repository is organized as follows:
- /Gerber: Contains the Gerber files necessary for PCB manufacturing.
- /BOM: Includes the bill of materials (BOM) listing all components required for assembly.
- /Documentation: Provides additional documentation, schematics, and datasheets related to Delta-S-M Ver.1.0.

## Cable pinout difference

Be carefull, as there is a very important difference in video cable pinout between v0.1, v1.0 and v1.2 and up.

**v0.1 and v1.0 boards video pinout:**

- 1 - Sync
- 2 - Red
- 3 - N/C
- 4 - Blue
- 5 - Green
- 6 - GND
- 7 - +5V

**v1.2 boards video pinout:**

- 1 - Sync
- 2 - GND
- 3 - Red
- 4 - Green
- 5 - Blue
- 6 - Audio
- 7 - +5V

V1.2 boards are compatible with original Delta-S and Delta-128 and could be connected with their cables.

## Making SCART cable
The best video quality could be achived with SCART cable with RGB mode. Delta S-M is capable of outputting native RGB signal and uses a SCART cable to connect to RGB-capable TVs. The picture below illustrates pinout of both SCART plug and DIN-7 plug.

SCART Pinout

15 - Red
11 - Green
7 - Blue
20 - Sync
16 - ADD 180 Ohm resistor between computer and SCART plug and connect it to pin 16 to enable switching to correct RGB mode. Direct +5V could DAMAGE YOUR TV!
5, 9, 13, 17 and 21 (metal case) - Ground




## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the Delta-S-M Ver.1.0 Gerber files as per the terms of the license.

For more details, refer to the [LICENSE](LICENSE) file.

---



![Delta-S-M Ver.1.0](https://example.com/board.png)
