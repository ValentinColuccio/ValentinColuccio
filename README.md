# 👋 Hi, I'm Valentín Coluccio

### 🤖 Mechatronics Engineer · Industrial robotics, machine vision and PLC

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/Embedded_C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Qt](https://img.shields.io/badge/PyQt5-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

I build systems that do something in the physical world. Right now that means integrating collaborative robots, industrial cameras and PLCs into production lines: automated quality control, robotic cells and internal logistics with AMRs.

I work as a project engineer at **eMoveSolutions**, an integrator of JAKA collaborative robots, SensoPart and OPT machine vision, iPlusMobot AMRs and Mitsubishi PLC automation. My work runs from bench setup to commissioning on the customer's floor — which usually means the interesting part is the day something doesn't work and nobody knows why.

Mechatronics Engineering degree from **Universidad Nacional de Lomas de Zamora (UNLZ)**, Argentina.

---

## 🔬 Featured projects

### 🫀 Preprocessor for Elvira — research, published

Graphical interface module built in PyQt5 and integrated into SALOME 9.13, acting as a preprocessor for the cardiac electrophysiology simulator Elvira. It centralizes mesh import, material and property definition, stimulus and solver configuration, and validated export of simulation files.

- Lead author, presented and published at **MECOM 2025** (Argentine Congress on Computational Mechanics)
- The research team that validated it estimated a **60-70% reduction** in simulation setup time
- Currently in use by PhD students in Spain and collaborators in Italy
- Developed under an **EVC-CIN 2024** research grant
- Published: https://doi.org/10.70567/mc.v42.ocsid8567

### 🏗️ Robotic tower crane — final degree project

<!-- Foto o GIF de la grúa acá -->

Scale storage and dispatch system built around a robotic tower crane. Incoming parts are identified by machine vision, stored in categorized positions, and dispatched on demand through voice commands.

The architecture is distributed across three units: a PC running vision, speech recognition and the dispatcher; a Raspberry Pi Zero 2 WH holding the control logic, live inventory and kinematics, reached over TCP sockets; and an ESP32 driving four stepper motors over UART. Vision runs on a SensoPart VISOR Object AI industrial camera triggered by an IR sensor, speech recognition on Vosk with a wake word, and the operator interface is a PyQt5 HMI with live video, unified logging and remote control of both machines.

Built by a team of two. I was responsible for the vision system, the Raspberry Pi implementation and the HMI.

`Python` · `PyQt5` · `Vosk` · `Raspberry Pi Zero 2 WH` · `ESP32` · `TCP sockets` · `SensoPart VISOR`

➡️ https://github.com/ValentinColuccio/Almacenamiento-con-Grua-Torre-Coluccio-Gomez

### 🪁 4-axis CNC hot-wire cutter — supervised professional practice

<!-- Foto de la máquina ensamblada acá -->

CNC machine with independent positioning at both ends of the cutting wire, for manufacturing variable-geometry airfoil profiles in expanded polystyrene for aeronautical prototypes. I redesigned a ten-year-old conceptual model to fit the components actually available, then built and integrated it.

Control architecture is distributed: a Raspberry Pi 4B handles operation and supervision while a GRBL controller generates the STEP/DIR signals, after discarding direct generation from the Pi due to the non-deterministic timing of general-purpose Linux.

`Raspberry Pi 4B` · `GRBL` · `G-code` · `bCNC` · `CATIA` · `SolidWorks` · `Fusion 360 (CAD/CAM)`

➡️ https://github.com/ValentinColuccio/2026_1C_PPS_CortadoraDePolifanCNC_Coluccio

---

## 🧰 Tools & technologies

| | |
|---|---|
| 🦾 **Robotics & automation** | JAKA collaborative robots · AMRs (load and roller) · Mitsubishi PLC and HMI · Modbus TCP, Ethernet, wired I/O |
| 👁️ **Machine vision** | SensoPart VISOR · OPT smart cameras · lens, filter and lighting selection · OpenCV |
| 💻 **Programming** | Python · PyQt5 · Embedded C · G-code / GRBL |
| 🔌 **Hardware** | Raspberry Pi · ESP32 · Arduino · stepper motors and drivers · 3D printing |
| 📐 **CAD/CAM** | CATIA · SolidWorks · Fusion 360 |

---

## 🤝 Open to

Project engineering, automation, robotics and R&D roles — in Argentina, remote or international.

## 📫 Contact

- 💼 LinkedIn: https://www.linkedin.com/in/valentin-coluccio-804301359/
- 📧 Email: valentincoluccio@gmail.com