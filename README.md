# Raspberry Pi GPIO Hat – For raspberry pi 4B based prototype that measures video delay

This repository contains the complete KiCad project files, Gerber output, and a .rar archive package intended for PCB manufacturing and modification. The design is a custom Raspberry Pi HAT (Hardware Attached on Top) tailored for GPIO interfacing with USB and RJ45 port alignment for an enclosure.

## 📷 Overview
 It features:
 
- **Raspberry Pi 40-pin GPIO header** for direct stacking.
- **Two push-button switches**:
  - `SW1`: Momentary tactile push button
  - `SW2`: SPDT switch footprint
- **Supporting components**:
  - Capacitors (10µF, 100nF) for decoupling
  - Resistors (e.g., 10Ω) for current limiting or signal conditioning
  - LED (D2) indicator
- A mostly top-layer signal layout with a ground pour to ensure good electrical performance.

## 📁 Contents
├── gerber/ # Gerber files for manufacturing

├── *.kicad_sch # Schematic

├── *.kicad_pcb # PCB layout

├── Gerbers.rar # Pre-packaged archive to send to PCB manufacturer

└── README.md # This file

🛠️ How to Use
For Fabrication:
Send the contents of the Gerbers.rar or the /gerber/ folder to your preferred PCB manufacturer. Most PCB suppliers accept this standard format.

For Modification:
Clone or download this repository.

Open the .kicad_pro file using KiCad (version 7+ recommended).

Modify the schematic or PCB layout as needed.

Re-export the Gerber files from KiCad.

📦 Recommended PCB Specs
2-layer board

1.6mm FR-4

📄 License
This project is open for any use. If you plan to commercialize it, please contact the original author or fork appropriately.
