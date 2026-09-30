# High-Power PWM Motor & Fan Speed Controller

A high-performance PWM-based speed controller designed for industrial DC motors and heavy-duty ventilation fans. This circuit provides robust speed regulation using an NE555 timer architecture and is capable of handling high voltages and high current loads.

## 🚀 Overview
This project was developed in **Altium Designer** to provide a reliable solution for controlling DC motors or industrial fans. It utilizes a parallel MOSFET configuration to minimize resistance and heat dissipation, and an onboard buck regulator for stable control-circuit power.

## 🛠 Key Features
* **PWM Generation:** Based on the reliable **NE555** timer IC for precise duty-cycle control.
* **High-Power Stage:** Features **4x IRFP4768** N-Channel Power MOSFETs in parallel to handle high-current loads efficiently.
* **Onboard Power Management:** Equipped with the **LM5008** high-voltage buck regulator, allowing the board to be powered directly from high-voltage DC lines.
* **Protection:** Includes bulk electrolytic capacitors for ripple filtering and diode protection for inductive loads.

## 📋 Technical Specifications
* **Control Input:** 0-100% Duty Cycle (via Potentiometer)
* **Switching Elements:** 4x IRFP4768 (TO-247 Package)
* **Voltage Regulation:** TI LM5008 Buck Regulator
* **Target Applications:** Industrial cooling fans, agricultural machinery motors, DC motor speed control.

## 📂 Repository Structure
* `/Hardware`: Contains Altium Designer project files (`.PcbDoc`, `.SchDoc`).
* `/Gerbers`: Production-ready Gerber files for PCB manufacturing.
* `/Docs`: Datasheets for key components (LM5008, NE555, IRFP4768).

## ⚠️ Disclaimer
*This project involves high-voltage and high-current circuitry. Please ensure proper heatsinking and safety precautions are taken during operation. Use at your own risk.*

## 📄 License
This project is licensed under the **MIT License**. Feel free to use, modify, and distribute for your own projects.
