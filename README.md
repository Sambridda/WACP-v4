# WACP v4.0: Automated Water Management System

An intelligent, distributed control system for residential water management. This project replaces manual monitoring with a closed-loop architecture using custom RF communication and modular hardware.

## 🛠️ Project Documentation
Detailed engineering reports are available in the [assets](./assets/) folder:
* **[Design Overview](./assets/Design%20Overview.pdf)** – Full system architecture and testing results.
* **[Algorithm Specification](./assets/Algorithm%20Specification.pdf)** – Logic for the BareBone-OS Protocol.

## 🔌 Hardware Design (KiCad)
The system uses custom-designed 2-layer PCBs for distributed control nodes.

### Master Control Unit
| 2D Layout | 3D Render |
| :--- | :--- |
| ![Master 2D](./assets/Master_Editor.jpg) | ![Master 3D](./assets/Master_Render.jpg) |
*View the [Master Schematic PDF](./assets/Master_Schematic.pdf)*

### Station Nodes (Sump & Roof)
| 2D Layout | 3D Render |
| :--- | :--- |
| ![Station 2D](./assets/Station_Editor.jpg) | ![Station 3D](./assets/Station_Render.jpg) |
*View the [Station Schematic PDF](./assets/Station_Schematic.pdf)*

## 🛰️ Technical Features
* **Custom Protocol:** Reliable 433 MHz RF communication with a custom packet structure.
* **Safety Logic:** Dry-run protection via ACS712 current sensing and ultrasonic feedback.
* **Modular Design:** Independent power regulation and signal isolation on-board.
