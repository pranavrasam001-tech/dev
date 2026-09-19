# RP2040 PCB

## About the Project

This is a custom PCB designed in KiCad around the RP2040 microcontroller. The design includes USB Type-C connectivity, external flash memory, power regulation, a crystal oscillator, push-button control, and pin headers for external connections.

The project contains the complete schematic and PCB layout along with the Bill of Materials and Gerber manufacturing files.

---

## Features

- RP2040 microcontroller
- USB Type-C USB 2.0 interface
- W25Q128JVS external flash memory
- 3.3V voltage regulation
- External crystal oscillator
- Push button
- 20-pin header connectors
- 3-pin header connector
- SMD component design
- Two-layer PCB layout
- Gerber manufacturing files
- BOM exported as CSV

---

## Components Used

- RP2040
- W25Q128JVS
- MCP1700x-330xxTT
- USB Type-C Receptacle
- Crystal
- Push Button
- 1x20 Pin Headers
- 1x03 Pin Header
- Resistors
- Capacitors

---

##Images
<img width="940" height="625" alt="image" src="https://github.com/user-attachments/assets/e55872c3-f013-4ef9-be9d-02bd8d661373" />
<img width="585" height="831" alt="image" src="https://github.com/user-attachments/assets/3a0b0596-5311-4f3b-b252-5384c3d7fa0d" />

---

## What I Did

- Created the schematic in KiCad.
- Added the RP2040 and supporting components.
- Added USB Type-C connectivity.
- Added external flash memory.
- Designed the power regulation section.
- Added the crystal oscillator circuit.
- Added required resistors and capacitors.
- Added push-button and header connections.
- Connected the required USB, power, ground, GPIO, QSPI, and clock signals.
- Created the PCB layout from the schematic.
- Assigned and placed component footprints.
- Routed the PCB connections.
- Prepared the PCB manufacturing layers.
- Generated the Gerber files.
- Generated the Bill of Materials.

---

## PCB Design

The PCB design uses front and back copper layers along with solder mask, silkscreen, paste, and edge-cut layers.

The design includes footprints for the RP2040, USB connector, external flash, regulator, crystal, headers, switch, resistors, and capacitors.

---

## What I Learned

- Creating schematics in KiCad
- Working with the RP2040
- USB Type-C connections
- External flash memory connections
- Power regulation design
- Component footprint selection
- PCB component placement
- PCB routing
- Working with multilayer PCB design files
- Generating a Bill of Materials
- Generating Gerber manufacturing files

---

## Project Files


```text
RP2040-PCB
│
├── Dev.kicad_pro
├── Dev.kicad_sch
├── Dev.kicad_pcb
├── Dev.csv
│
├── Gerber Files
│   ├── Dev-F_Cu.gbr
│   ├── Dev-B_Cu.gbr
│   ├── Dev-F_Mask.gbr
│   ├── Dev-B_Mask.gbr
│   ├── Dev-F_Silkscreen.gbr
│   ├── Dev-B_Silkscreen.gbr
│   ├── Dev-F_Paste.gbr
│   ├── Dev-B_Paste.gbr
│   ├── Dev-Edge_Cuts.gbr
│   └── Dev-job.gbrjob
│
└── README.md

GitHub: https://github.com/pranavrasam001-tech/dev.git

