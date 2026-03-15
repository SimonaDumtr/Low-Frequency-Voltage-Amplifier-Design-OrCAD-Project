# 🔊 Low-Frequency Voltage Amplifier Design

This project presents the design, simulation, and PCB layout of a **low-frequency voltage amplifier** developed as part of the *Electronic Devices and Circuits* course at the Faculty of Electronics, Telecommunications and Information Technology.

The amplifier was designed to meet specific electrical parameters and to operate reliably across a defined temperature range.

---

## 📌 Project Overview

The project involves the complete development process of an analog electronic module, including:

- circuit design and theoretical analysis
- functional simulations using PSPICE
- PCB layout design
- verification of electrical parameters and operating conditions

The amplifier provides a **voltage gain of approximately 10** while maintaining stable operation and low distortion.

The circuit architecture includes several functional blocks such as a differential stage, current mirrors, and a class-AB output stage.

According to the design requirements, the amplifier operates with an input signal of **750 mV** and a load resistance of **75 Ω**. :contentReference[oaicite:0]{index=0}

---

## ⚙️ Circuit Architecture

The amplifier is composed of several key stages:

- Differential input stage for signal comparison
- Current mirror circuits for bias stabilization
- Voltage amplification stage
- Class-AB output stage for improved efficiency
- Negative feedback loop for gain stabilization

The negative feedback network ensures that the amplifier gain remains stable and predictable. The resulting voltage gain is: Av = ((R5 + R10) / R4) + 1 ≈ 10


---

## 🛠️ Technologies and Tools

- **OrCAD Capture**
- **PSpice Simulation**
- **OrCAD PCB Editor**
- Analog circuit design techniques
- PCB design and layout optimization

---

## 🧪 Simulation and Testing

The circuit performance was validated using several simulations:

### Transient Analysis
The output signal follows the input signal with a gain of approximately **10×**, confirming correct circuit functionality.

### Frequency Response (Bode Analysis)
The frequency response analysis shows a gain close to **20 dB**, corresponding to the expected amplification factor.

### Temperature Stability
The amplifier was tested at three temperatures:

- **0°C**
- **25°C**
- **70°C**

The simulations showed minimal variation in output voltage (less than **100 mV**), demonstrating stable circuit operation. :contentReference[oaicite:1]{index=1}

---

## 🖥️ PCB Design

The amplifier was implemented on a **two-layer PCB** with the following characteristics:

- Board size: **40 × 40 mm**
- Material: **FR-4**
- Copper thickness: **18 μm**
- Board thickness: **1.6 mm**
- Two electrical layers (TOP and BOTTOM)

The PCB layout was designed following industry standards for trace width, spacing, and component placement. :contentReference[oaicite:2]{index=2}

---

## 🎯 Learning Objectives

This project was developed to gain practical experience in:

- analog circuit design
- electronic component selection
- circuit simulation using PSpice
- PCB layout design
- signal integrity considerations
- electronic system verification

---

## 📚 References

- Analysis and Design of Analog Integrated Circuits – P.R. Gray  
- Circuite Electronice Fundamentale – G. Brezeanu  
- OrCAD PCB Design Documentation
