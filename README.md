
# 🎚️ Five-Band Analog Audio Equalizer

A fully functional five-band analog audio equalizer covering the full audio spectrum (20 Hz – 20 kHz) This project was developed for the EN2091 – Laboratory Practice and Projects module at the University of Moratuwa.

---

## 📦 Repository Structure

```

Five-Band-Equalizer/
├── schematics/           # Circuit diagrams (Altium files, PDF exports)
├── pcb/                  # PCB layout files and Gerber outputs
├── enclosure/            # SolidWorks CAD models and drawings
├── docs/                 # Theory write-ups and filter design calculations
└── README.md             # Project overview and instructions

```

---

## 🔍 Project Overview

This project implements a real-time analog equalizer with five adjustable bands. Users can boost or attenuate specific frequency ranges via Multiple-Feedback (MFB) Butterworth filters and gain stages, while LED bar-graph displays driven by LM3914 ICs provide instant visual feedback.

---

## 🔧 Project Highlights

- **Filter Design**: 4th-order Butterworth band-pass filters using MFB topology  
- **Gain Control**: Inverting op-amp stages with front-panel potentiometers  
- **Display**: LED bar-graph per band via LM3914 drivers  
- **Power Supply**: Dual ±15 V rails using LM7815 & LM7915 regulators  
- **Audio I/O**: Standard 3.5 mm AUX input/output jacks  

---

## 🛠️ Tools & Technologies

- **Simulation**: LTSpice, Proteus  
- **PCB Layout**: Altium Designer  
- **Enclosure CAD**: SolidWorks  
- **Active Components**: TL072 dual op-amps, LM3914 LED drivers  
- **Passives & Connectors**: Precision capacitors, metal-film resistors, potentiometers  

---

## 📐 Frequency Bands

| Band               | Frequency Range   | Center Frequency |
|--------------------|-------------------|------------------|
| **Bass**           | 20 Hz – 300 Hz     | 77.46 Hz         |
| **Lower Midrange** | 300 Hz – 1 kHz     | 547.72 Hz        |
| **Midrange**       | 1 kHz – 4 kHz      | 2 kHz            |
| **Upper Midrange** | 4 kHz – 10 kHz     | 6.32 kHz         |
| **Treble**         | 10 kHz – 20 kHz    | 14.14 kHz        |

---

## 👥 Team & Contributions

| Team Member                  | Contribution                                                   |
|------------------------------|----------------------------------------------------------------|
| **Minura Ashen** (me)        | Circuit design, LTSpice/Proteus simulation, PCB testing & docs |
| **Ravindu Kuruppuarachchi**  | Equalizer PCB layout, prototyping, signal integrity checks     |
| **Kaveeshwara Bandara**      | LED bar-graph & power PCB design, driver testing               |
| **Nirwan Jayatissa**         | Enclosure CAD design, mechanical integration & assembly tests  |

---

## 📚 References

- TL072 Datasheet — Texas Instruments  
- LM3914 Datasheet — Texas Instruments  
- Butterworth Filter Theory — Standard signal-processing texts
```
