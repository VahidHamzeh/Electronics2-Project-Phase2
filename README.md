![Design](https://img.shields.io/badge/Analysis-Frequency_Response-blue?style=for-the-badge&logo=microchip&logoColor=white)
![Simulation](https://img.shields.io/badge/Simulation-LTspice-red?style=for-the-badge&logo=siemens&logoColor=white)
![Metrics](https://img.shields.io/badge/Metrics-GBW_&_Phase-orange?style=for-the-badge&logo=mathworks&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=github&logoColor=white)
# Electronics2 | Project | Phase2

## Project Description
This repository contains the second phase of the Electronics II course project, focusing on the frequency response analysis and small-signal modeling of a MOSFET differential amplifier.

## Circuit Block Architecture
The design follows a modular approach for the analog integrated circuit, ensuring optimal biasing and signal processing performance. The circuit is segmented into the following stages:

<img width="882" height="370" alt="Screenshot 1405-03-27 at 5 42 35 PM" src="https://github.com/user-attachments/assets/a26704da-b12b-4a4d-9ced-e49dd2092a20" />

* **Input Stage (Red):** Cascode differential input stage to maximize gain and frequency response.
* **Buffer (White):** Impedance matching and signal buffering.
* **Biasing Sources (Purple):** Precision DC current sources for stable operation.
* **Current Mirrors (Green):** Active loads and biasing for current steering.
* **Vbe Multiplier (Blue):** Bias voltage generation for class-AB output stages.
* **Output Stage (Pink):** Power stage designed for high-current driving capability.
* **Feedback Network (Orange):** Closing the loop for linearity and gain control.


* **Magnitude Response:** The circuit exhibits a stable mid-band gain as predicted by theoretical small-signal analysis.
* **Phase Margin:** Phase shift analysis confirms stability and bandwidth limits of the CMOS architecture.

## Repository Contents
- **/Simulations:** Contains all LTspice (.asc) files.
- **/Report:** Contains the final technical report (PDF).

## Technical Specifications
- **Topology:** CMOS Differential Amplifier.
- **Analysis:** Small-signal AC analysis, gain-bandwidth product (GBW) calculation, and frequency response verification.
- **Simulation Tool:** LTspice XVII.

## Project Status
- [x] Design & Theoretical Analysis
- [x] LTspice Simulation
- [x] Documentation

## Contact
Vahid Hamzeh | Sharif University of Technology
