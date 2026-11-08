# Universal Baseboard

Prototyping Platform for AMD Kria K24/K26 and Sundance SoM6/SoM7

The Universal Baseboard is a flexible prototyping platform for AMD Kria K24/K26 and Sundance SoM6/SoM7 SoMs. It enables maximum I/O flexibility by extensive, configurable I/O muxing for the transceiver ports as well as for the "conventional" I/O signals. 

The on-board interfaces are streamlined to the essentials required for SoM startup and basic connectivity (i.e., JTAG/UART, SD Card, Ethernet). All remaining interfaces are connected to FMC, SYZYGY, and PMOD headers. This approach makes the baseboard the ideal solution for diverse prototyping demands and allows for high reusability of the front-end modules.

Furthermore, with the optional Sync Board, it is possible to synchronize all peripherals to a single, high-precision clock source, thus making the platform suitable for high-frequency, low-jitter data acquisition and signal processing applications.


## Repository content

PCB design data for Altium Designer

## Repository structure
| **Folder**  | **Content** |
|-------------|-----------------------|
| 01 license | license terms for this project |
| 02 lib | integrated project library  |
| 03 sch | Everything related to schematics |
| 04 pcb | Everything related to pcb layout |
| 09 output | Generated Outputs; Gerber, Drill, BOM etc.|
| 10 docs | Documentation |

***

## Usage
Clone the repo and open the project file with Altium Designer. I usually update Altium Designer every quarter or so. So it should work with the latest version of the tool.

## Support
If you have questions or need further documentation regarding the hardware design please open an issue in this repo.

## Roadmap
The design is still in the prototyping phase. The current plan is for the design to be ready for production after the next iteration. The next version will therefore mainly include bug fixes and obvious optimizations.
Since we are facing increasing shortages of various materials and components, it is difficult to predict when the product will be available for order.

Planned extension boards:
- Sync Board with LMK05028 network synchronizer, OCXO, GPSDO 
- SYZYGY TXR-4 board for NVMe PCIe4x SSD
- SYZYGY TXR-2 board for USB3/SATA (or SATA SSD)
- SYZYGY TXR-2 board for NVMe PCIe2x SSD
- SYZYGY TXR-2 board for DP 2-lanes
- SYZYGY TXR-2 board for 2xSATA
- FMC-to-SYZYGY Adapters

## Contributing
If you are interested in contributing to the project, (e.g. by extension-board or firmware development) please contact me via support@heosys.de.
Even though the baseboard has been designed with Altium Designer (and will remain in that ecosystem), Kicad designs for extensions are welcome, too. 

## License
Copyright 2026 Matthias Häfner

This source describes Open Hardware and is licensed under the CERN-OHL-S v2.
You may redistribute and modify this source and make products using it under the terms of the CERN-OHL-S v2 (https://cern.ch/cern-ohl).
This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-S v2 for applicable conditions.

## Project status
First prototypes build for extensive evalutation and testing
