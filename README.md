# STM32 PCB Design Project (Altium)

## 📌 Overview
This project presents a custom-designed **STM32F411-based PCB** developed in **Altium Designer**, integrating power management, USB interface, debugging support, and sensor interfacing.

The design demonstrates complete hardware development workflow from schematic to PCB layout.

---

## 🏗️ System Architecture

The PCB consists of three major sections:

### 1. Power Supply
- USB input (5V)
- LDO regulator (AMS1117) for 3.3V output
- Decoupling capacitors for stable operation

### 2. Microcontroller Section
- STM32F411CEU6 (ARM Cortex-M4)
- External 24 MHz crystal oscillator
- Boot configuration and reset circuitry
- SWD debugging interface

### 3. Sensor Interface
- MPU6050 IMU (I2C communication)
- Interrupt pin for motion detection

---

## 🔧 Hardware Features
- STM32F411 microcontroller (high-performance ARM Cortex-M4)
- USB-powered system with onboard regulation
- IMU integration (MPU6050)
- SWD programming/debugging support
- Proper decoupling and grounding design

---

## 📐 PCB Design
- Designed in **Altium Designer**
- 2-layer PCB
- Clean routing and component placement
- Power and signal integrity considerations included

---

## 🖥️ Design Files
- Altium schematic (.SchDoc)
- PCB layout (.PcbDoc)
- Gerber files (ready for fabrication)

---

## 📸 Preview
## 📄 Schematic

<p align="center">
  <img src="https://raw.githubusercontent.com/brijeshahirwar100/STM32_PCB_Design_Project/main/STM32_PCB_Design_Project/Schematic/Schematic.png" width="800"/>
</p>

## 📐 PCB Layout (2D)

<p align="center">
  <img src="https://raw.githubusercontent.com/brijeshahirwar100/STM32_PCB_Design_Project/main/STM32_PCB_Design_Project/PCB/PCB_Layout_2D.png" width="800"/>
</p>
## 📐 PCB Layout (3D)

<p align="center">
  <img src="https://raw.githubusercontent.com/brijeshahirwar100/STM32_PCB_Design_Project/main/STM32_PCB_Design_Project/PCB/PCB_Layout_3D.png" width="800"/>
</p>

## 🚀 Skills Demonstrated
- PCB Design (Altium Designer)
- Embedded Hardware Design
- Power Electronics (LDO regulation)
- Microcontroller System Design
- Sensor Interfacing (I2C)

---

## 👨‍💻 Author
**Brijesh Ahirwar**  
B.Tech ECE, IIT (BHU) Varanasi

---

## 📄 License
MIT License
