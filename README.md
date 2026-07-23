# 🎵 LM386 Audio Amplifier - Schematic & Design

A personal schematic design project for a low-voltage audio power amplifier based on the **LM386** integrated circuit, developed using **OrCAD Capture**.

This project was built as a practical exercise to apply analog electronics design concepts and core **Signal Integrity** principles.

---

## 🖼️ Schematic Preview

![LM386 Audio Amplifier](AMPLIFIER_PCB.PNG)

---

## 🛠️ Technical Specifications & Features

* **Main IC:** LM386 (Low Voltage Audio Power Amplifier)
* **Voltage Gain:** Configured to **200** (via 10µF capacitor C2 connected between pins 1 and 8)
* **Volume Control:** 10kΩ potentiometer (R1) at the audio input stage
* **Stability & Noise Suppression (Signal Integrity):**
  * **Zobel / Boucherot Network** (C4 = 47nF, R2 = 10Ω) at the output to prevent high-frequency oscillations.
  * Power supply decoupling bypass capacitor C3 (100nF) to filter VCC supply noise.
  * Output coupling capacitor C1 (250µF) to block DC offset from the speaker.

---

## 📁 Repository Structure

* OrCAD Capture source files (`.DSN`, `.OPJ`)
* High-resolution schematic preview (`.PNG`)
