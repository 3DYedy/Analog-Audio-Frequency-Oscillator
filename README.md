# Analog Audio Frequency Oscillator

## 1. Project Overview
This project consists of the design, simulation, and physical implementation of a sinusoidal audio frequency oscillator. It was developed as a university laboratory project following a strict set of technical constraints.

### Technical Specifications (N=1)
* **Target Waveform:** Sinusoidal.
* **Power Supply:** 11V (Unipolar).
* **Frequency Range:** Tunable between 100 Hz and 1 kHz.
* **Output Amplitude:** Adjustable between 0 and 100 mV.
* **Load Resistance:** 400 Ω (Purely resistive).

## 2. Design Process
The design phase involved the analytical study of three feedback networks: **Wien Bridge, T-bridged, and Twin-T**. 

1.  **Analytical Calculation:** Determined the component values (R, C) to satisfy the frequency oscillation condition $f = 1/(2\pi RC)$.
2.  **SPICE Simulation:** Validated the circuit stability and output swing using LTSpice/OrCAD PSpice before moving to hardware.

## 3. Hardware Implementation
The PCB was designed in **OrCAD Capture & Layout**, focusing on a compact footprint and signal integrity.

### Schematic Diagram
<img width="763" height="590" alt="image" src="https://github.com/user-attachments/assets/814ba133-5eda-4ef9-ae57-f998b56f6002" />

### PCB Layout (2D/3D)
<img width="804" height="816" alt="image" src="https://github.com/user-attachments/assets/7adb6fac-6c30-47ca-9734-40e8a822a0ef" />


## 4. Results & Validation
The circuit was tested in the laboratory using a digital oscilloscope and a 400 Ω load.
* **Measured Frequency:** Confirmed 100 Hz - 1 kHz range.
* **Signal Integrity:** Minimal distortion observed in the sinusoidal output.

<img width="1875" height="685" alt="image" src="https://github.com/user-attachments/assets/05338b26-3e67-4272-a07e-18c7cd557fd8" />

## 5. Tools Used
* **OrCAD Capture & PCB Editor:** Schematic and PCB Design.
* **OrCAD:** Functional simulation.
* **Laboratory Equipment:** Oscilloscope, Multimeter, Power Supply.
