# WACP v4.0: Automated Water Management System

An intelligent, distributed control system designed for residential water resource management. This project replaces manual monitoring with a semi-automated, closed-loop architecture using custom RF communication.

## 🚀 Key Features
* **Distributed Sensing:** Real-time water level monitoring using Ultrasonic sensors.
* **Custom Protocol:** Reliable 433 MHz RF communication using a custom-built packet structure (BareBone-OS Protocol).
* **Safety First:** Integrated current sensing (ACS712) for dry-run protection and stall detection.
* **Custom Hardware:** Designed modular PCBs in KiCad for Master and Station nodes.

## 🛠️ Tech Stack
* **Microcontrollers:** Arduino, ESP8266
* **Communication:** RF 433 MHz (HC-12 / Custom Protocol)
* **Design Tools:** KiCad (PCB), SolidWorks (CAD), FluidSIM
* **Programming:** C++ (Embedded)

## 📂 Deep Dive Documentation
I have documented the full engineering process in detail:
* [Design Overview](./Design%20Overview.pdf) - Includes system architecture, PCB layouts, and testing results.
* [Algorithm Specification](./Algorithm%20Specification.pdf) - Detailed logic for the custom BareBone-OS communication protocol.

## 📈 System Performance
The system features safety interlocks and "Fail-Safe" logic to prevent manual errors and hardware damage, as validated in my experimental testing.
