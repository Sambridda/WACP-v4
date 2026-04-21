# WACP v4.0: Automated Water Management System

An intelligent, distributed control system for residential water management. This project replaces manual monitoring with a closed-loop architecture using custom RF communication and modular hardware.

## 🛠️ Project Documentation
Detailed engineering reports are available in the [assets](./assets/) folder:
* **[Design Overview](./assets/Design%20Overview.pdf)** – Full system architecture and testing procedures.
* **[Algorithm Specification](./assets/Algorithm%20Specification.pdf)** – Logic for the BareBone-OS Protocol.

## 🔌 Hardware Design (KiCad)

### 🧠 Master Control Unit
| Schematic (PDF) | 2D Layout | 3D Render |
| :--- | :--- | :--- |
| [Download PDF](./assets/CONTROL%20PCB.pdf) | ![Master 2D](./assets/Control%20editor.jpg) | ![Master 3D](./assets/Control%20render.jpg) |

---

### 🕳️ Sump Station (SC1)
| Schematic (PDF) | 2D Layout | 3D Render |
| :--- | :--- | :--- |
| [Download PDF](./assets/SC2%20PCB.pdf) | ![Sump 2D](./assets/SC2%20editor.jpg) | ![Sump 3D](./assets/SC2%20render.jpg) |

---

### 🏠 Roof Station (SC2)
| Schematic (PDF) | 2D Layout | 3D Render |
| :--- | :--- | :--- |
| [Download PDF](./assets/SC1%20PCB.pdf) | ![Roof 2D](./assets/SC1%20editor.jpg) | ![Roof 3D](./assets/SC1%20render.jpg) |

## 🛰️ Technical Features
* **Custom Protocol:** Reliable 433 MHz RF communication with a custom packet structure.
* **Safety Logic:** Dry-run protection via ACS712 current sensing and ultrasonic feedback.
* **Modular Design:** Independent power regulation and signal isolation on-board.

## 🚧 Current Build Status
* [x] System Architecture & PDF Documentation
* [x] KiCad PCB Design (Master, SC1, SC2)
* [ ] **Physical Prototyping (In Progress):**
    * Currently assembling SC1 (Sump Station) on high-density perfboard.
    * Validating power regulation and RF communication range.
