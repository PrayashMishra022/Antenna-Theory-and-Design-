# Antenna-Theory-and-Design-
A Complementary Folded Line Metamaterial (CFL-MTM) Loaded MIMO Antenna has been simulated for S band wireless applications.

# CFL-MTM Loaded MIMO Antenna for S-Band Wireless Applications

This repository contains the design, simulation, and performance analysis of a **Complementary Folded-Line Metamaterial (CFL-MTM) Loaded MIMO Antenna**, developed as part of the Antenna Theory and Design course (20ECE311T) at Pandit Deendayal Energy University.

## 📘 Abstract

The proposed MIMO antenna leverages **CFL-MTM structures** and an **Asymmetric Coplanar Waveguide (ACPW)** feed to enhance impedance matching, mutual coupling suppression, gain, and bandwidth. Designed for S-band wireless applications (3.121–4.277 GHz), this antenna demonstrates significant performance improvements and is simulated using **ANSYS HFSS**.

## 🧪 Features & Performance

- **Operating Band**: 3.121 GHz – 4.277 GHz (S-band)
- **Bandwidth**: 1156 MHz
- **Return Loss (S11)**: -43 dB
- **Isolation (S21)**: -24 dB
- **Peak Gain**: 2.28 dB
- **Radiation Efficiency**: > 75%
- **MIMO Metrics**:
  - Envelope Correlation Coefficient (ECC) < 0.02
  - Diversity Gain (DG) ≈ 10 dB
  - Total Active Reflection Coefficient (TARC) < -3 dB
  - Channel Capacity Loss (CCL) < 0.1 bps/Hz

## 🧱 Design Overview

The antenna is implemented in four stages:
1. **Basic Microstrip Patch**
2. **CFL-MTM Integration**
3. **Two-Port MIMO Configuration**
4. **Optimized Final Antenna**

**Substrate**: FR-4 (εr = 4.4, Thickness = 1.6 mm)  
**Feeding**: Asymmetric Coplanar Waveguide (ACPW)  
**Spacing Between Elements**: 7 mm (~0.093λ at 4 GHz)

## 🛠️ Simulation Tools

- **Software**: ANSYS HFSS (2023 R2)
- **Simulation Type**: Full-wave 3D EM Simulation (FEM)
- **Frequency Sweep**: 2 GHz to 5 GHz (10 MHz resolution)
- **Key Outputs**:
  - S-parameters (S11, S21)
  - Gain and VSWR plots
  - 3D Radiation Patterns
  - Field and Surface Current Distributions

## 🧾 File Structure
📁 CFL-MTM-MIMO-Antenna
│
├── 📄 README.md # Project overview and usage
├── 📁 HFSS_Design_Files # HFSS models and CAD geometry
├── 📁 Simulation_Outputs # S11, S21, Gain, VSWR plots
├── 📄 Antenna_Report.pdf # Full technical report with results
└── 📁 References # Academic sources and background papers


## 📝 Summary of Results

| Parameter                | Value                          |
|--------------------------|--------------------------------|
| Resonant Frequency       | 4 GHz                          |
| Bandwidth                | 1156 MHz (3.121–4.277 GHz)     |
| Peak Gain                | 2.28 dB                        |
| Radiation Efficiency     | > 75%                          |
| Isolation (S21)          | -24 dB                         |
| Envelope Correlation (ECC)| < 0.02                        |
| Diversity Gain (DG)      | ~10 dB                         |
| TARC                     | < -3 dB                        |
| Channel Capacity Loss    | < 0.1 bps/Hz                   |

## 📊 Performance Enhancements

- **Tooth Structure Optimization**: Enhanced electrical length and bandwidth
- **Slot Length Modifications**: Targeted tuning of resonant frequency
- **ACPW Feed**: Broader bandwidth and impedance matching
- **CFL-MTM Loading**: High isolation with compact footprint

## 🚀 Future Scope

- **Fabrication and Measurement** in an anechoic chamber
- **Multiband Design** for LTE, Wi-Fi, and 5G sub-6 GHz
- **Massive MIMO Scaling** for 4-, 8-, or 16-port arrays
- **Advanced Substrates** like Rogers RT/Duroid for improved efficiency

## 📚 References

1. Mood & Pandeeswari, 2024 – *CFL-MTM MIMO Antenna for S-Band*
2. Khan & Lee, 2024 – *MIMO Antennas for 5G Applications*
3. Farahani et al., 2017 – *Mutual Coupling Reduction via Metamaterials*
4. Yusuf & Gong, 2024 – *Beamsteering with Mutual Coupling Management*
5. Arun et al., 2014 – *DGS and Compact Antenna Design*

*(Full citations available in the report.

## 👨‍🎓 Authors

- **Kanishk Munot** (22BEC023)  
- **Prayash Mishra** (22BEC046)  

Mentor: **Dr. Vivek Pandit** and **Dr. Dhaval Pujara** 
Department of Electronics and Communication Technology  
Pandit Deendayal Energy University, Gandhinagar, India

---

> 📡 This project showcases how metamaterial integration can significantly boost the performance of compact MIMO antennas, making them ideal for high-efficiency, high-isolation wireless communication systems such as 5G, radar, and IoT.

