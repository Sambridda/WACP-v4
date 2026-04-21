# WACP v4.0: Automated Water Management System

An intelligent, distributed control system for residential water management. This project replaces manual monitoring with a closed-loop architecture using custom RF communication and modular hardware.

## 🛠️ Project Documentation
Detailed engineering reports are available in the [assets](./assets/) folder:
* **[Design Overview](./assets/Design%20Overview.pdf)** – Full system architecture and testing results.
* **[Algorithm Specification](./assets/Algorithm%20Specification.pdf)** – Logic for the BareBone-OS Protocol.

## 🔌 Hardware Design (KiCad)

### 🧠 Master Control Unit
| Schematic (PDF) | 2D Layout | 3D Render |
| :--- | :--- | :--- |
| [Download PDF](./assets/Master_Schematic.pdf) | ![Master 2D](./assets/Master%20Editor%20Image.jpg) | ![Master 3D](./assets/Master%20Render%20Image.jpg) |

---

### 🕳️ Sump Station (SC1)
| Schematic (PDF) | 2D Layout | 3D Render |
| :--- | :--- | :--- |
| [Download PDF](./assets/Sump%20Station%20Schematic.pdf) | ![Sump 2D](./assets/Sump%20Station%20Editor%20Image.jpg) | ![Sump 3D](./assets/Sump%20Station%20Render%20Image.jpg) |

---

### 🏠 Roof Station (SC2)
| Schematic (PDF) | 2D Layout | 3D Render |
| :--- | :--- | :--- |
| [Download PDF](./assets/Roof%20Station%20Schematic.pdf) | ![Roof 2D](./assets/Roof%20Station%20Editor%20Image.jpg) | ![Roof 3D](./assets/Roof%20Station%20Render%20Image.jpg) |

## 🛰️ Technical Features
* **Custom Protocol:** Reliable 433 MHz RF communication with a custom packet structure.
* **Safety Logic:** Dry-run protection via ACS712 current sensing and ultrasonic feedback.
* **Modular Design:** Independent power regulation and signal isolation on-board.
