# HumidityDetector

## Project Overview
This repository showcases the **Humidity Detector** project developed as part of a university course on CAD for Electronics. The project involved designing and implementing a two-layer PCB, starting from an initial schematic. The system includes a humidity sensor, amplification stages, a bistable RS latch, and a relay-controlled output for automated control of an external load.

## Tools and Technologies
- **Software**: OrCAD Capture CIS 17.2 Lite
- **Design Features**:
  - Two-layer PCB design
  - Manual reset functionality
  - Protection against voltage surges (diode protection circuit)
  - Components exclusively mounted on the top layer

## Repository Structure
```
Humidity-Detector-Project/
├── Documentation/
│   ├── Project_Report.pdf     # Full report detailing the design and implementation
│   ├── Schematics.pdf         # Schematic design of the project
│   ├── PCB_Layout.pdf         # PCB layout in PDF format
├── Images/
│   ├── Schematic_Preview.png  # Preview image of the schematic
│   ├── PCB_Layout_Top.png     # Top layer of the PCB
│   ├── PCB_Layout_Bottom.png  # Bottom layer of the PCB
├── LICENSE                    # License file for the project
└── README.md                  # This file
```

## Features of the Design
- **Humidity Detection**:
  - The system detects humidity using copper electrodes.
  - When a conductive connection forms between electrodes, the circuit triggers the relay.
- **Signal Amplification**:
  - Transistor stages amplify the signal from the humidity sensor.
- **Control Logic**:
  - An RS latch maintains the state of the output until reset.
- **Protection**:
  - Diode circuitry protects the relay driver transistor from voltage surges.

## How to View
1. Open the `Documentation/` folder to access the full project report and schematic/PCB designs.
2. View images in the `Images/` folder for quick previews of the schematic and PCB layout.

## Disclaimer
This project was developed as part of a university course at **Faculty of Electronics, Telecommunications, and Information Technology || University POLITEHNICA Bucharest **. 
The files and designs provided here are for educational and demonstration purposes only.

## License
This project is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to share and adapt the material as long as you provide appropriate credit.

