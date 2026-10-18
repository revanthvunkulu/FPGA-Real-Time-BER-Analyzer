# FPGA-Based Real-Time BER Analyzer

**An FPGA-based project for data transmission and Bit Error Rate (BER) analysis using Verilog HDL.**

## 📌 Project Overview

The **FPGA-Based Real-Time BER Analyzer** is a digital communication project focused on transmitting data, receiving the transmitted data, and evaluating transmission accuracy using Bit Error Rate (BER).

The project aims to demonstrate how digital hardware can be used to analyze communication reliability by comparing transmitted data with received data and identifying bit errors.

This repository currently contains project photographs and documentation. Verilog source code, simulation results, and hardware validation details will be added as the project progresses.

## 🎯 Objectives

- Understand digital data transmission using FPGA hardware.
- Explore the implementation of communication systems using Verilog HDL.
- Study Bit Error Rate measurement in digital communication.
- Compare transmitted and received data to identify bit errors.
- Understand how FPGA technology can support communication testing and analysis.

## 🏗️ Proposed System Architecture

The planned system follows this data flow:

```text
          PC / User-Defined Data
                    |
                    v
                UART RX
                    |
                    v
           Original Data Buffer
                    |
                    v
             Channel Transmitter
                    |
                    v
          Physical Communication
                 Channel
                    |
                    v
              Channel Receiver
                    |
                    v
           Data Comparison Logic
                    |
                    v
            BER Counter / Logic
                    |
                    v
              UART TX to PC
```

*Note: This diagram represents the planned architecture. The final implementation may differ depending on the hardware setup and available interfaces.*

## 📊 Bit Error Rate (BER)

Bit Error Rate is a measurement used to evaluate the reliability of a digital communication system.

\[
\mathrm{BER}=\frac{\text{Number of erroneous bits}}{\text{Total number of transmitted bits tested}}
\]

For example, if 5 errors are detected among 10,000 tested bits:

\[
\mathrm{BER}=\frac{5}{10000}=0.0005
\]

A lower BER generally indicates more reliable data transmission under the tested conditions.

## 🛠️ Technologies and Tools

- **HDL:** Verilog HDL *(planned implementation)*
- **Hardware Platform:** FPGA development board
- **Design and Simulation:** AMD/Xilinx Vivado *(intended tool, if used)*
- **Communication Concept:** Digital data transmission
- **Performance Metric:** Bit Error Rate (BER)

## 📷 Project Gallery

Project photographs are included in this repository to document the hardware setup, development process, and project progress.

See the project images in the repository for visual documentation.

## 🚀 Planned Features

- User-defined data input from a PC.
- FPGA-based data transmission and reception.
- Comparison of transmitted and received data.
- Counting of total tested bits and erroneous bits.
- BER calculation and reporting.
- Simulation and hardware testing under different channel conditions.

## 📈 Current Project Status

**Status: Under Development**

The repository currently serves as a project documentation and photo gallery. The architecture and features described above represent the project direction and planned functionality; they should not be interpreted as completed or validated features until implementation and testing are documented.

Future updates may include:
- Verilog HDL source files.
- Testbenches and simulation waveforms.
- FPGA hardware implementation details.
- Test results and BER measurements.
- Additional project photographs and documentation.

## 👨‍💻 Author

**Revanth Vunkulu**

B.Tech – Electronics and Communication Engineering

Areas of Interest: FPGA Design, Verilog HDL, Digital Communication Systems, VLSI, and Embedded Systems.

## 📄 License

This project is shared for educational and learning purposes. A formal license can be added when the repository's sharing terms are decided.

## Images

<img width="1280" height="960" alt="WhatsApp Image 2026-10-17 at 11 41 26 AM" src="https://github.com/user-attachments/assets/53fd0ea8-4875-4281-b73e-008537bcf747" />
