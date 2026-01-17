<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Electronics</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Bipolar Junction Transistor (BJT)
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Eleni Tsalera, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.researchgate.net/profile/Eleni-Tsalera-2" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Lecturer in Applications
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, January 2023
</p>

---

# Project Overview

This repository contains the laboratory report for **Project 5**, focusing on the study and analysis of a **Bipolar Junction Transistor (BJT)** operating in a **common emitter circuit configuration**. The project combines **theoretical calculations**, **software simulations**, and **experimental laboratory measurements**.

---

## Table of Contents

| Section | Folder / File | Description |
|--------:|---------------|-------------|
| 1 | `assign/` | Assignment material |
| 1.1 | `assign/Exercise-8th-Transistor.pdf` | Assignment description (English) |
| 1.2 | `assign/Άσκηση-8η-Τρανζίστορ.pdf` | Assignment description (Greek) |
| 2 | `docs/` | Theoretical documentation |
| 2.1 | `docs/Bipolar-Junction-Transistor.pdf` | BJT theory (English) |
| 2.2 | `docs/Διπολικά-Τρανζίστορ.pdf` | BJT theory (Greek) |
| 3 | `lab1/LabPNG/` | Lab 1 experimental images |
| 3.1 | `lab1/MultisimPNG/` | Lab 1 Multisim simulation images |
| 4 | `lab3/LabPNG/` | Lab 3 experimental images |
| 4.1 | `lab3/MultisimPNG/` | Lab 3 Multisim simulation images |
| 4.2 | `lab3/3a.jpg` | Lab 3 additional image |
| 5 | `LabPNG/` | General lab images and setups |
| 6 | `Notes/` | Notes, extra images, measurement screenshots, and data files |
| 7 | `README.md` | Repository overview and instructions |

---

## Project Contents

The report is structured into key sections centered on the **Common Emitter Circuit**:

- **Output Characteristics (I<sub>c</sub> = f(V<sub>ce</sub>))**  
  Detailed analysis of collector current versus collector–emitter voltage  
  *(Pages 6–33)*

- **Input Characteristics (I<sub>b</sub> = f(V<sub>be</sub>))**  
  Analysis of base current versus base–emitter voltage  
  *(Pages 34–57)*

- **Laboratory Questions**  
  Analytical responses to experiment-related questions  
  *(Pages 58–59)*

---

## Equipment and Components

The following equipment and components were used during the experimental phase:

- **MCP M21-7000A** – Analog & Digital Training System (Breadboard)  
- **MCP MT8045** – Digital Multimeter Bench  
- **Transistor** – BJT **BC107BP**  
- **Resistors** – 560 Ω, 10 kΩ  
- **Potentiometers** – 100 kΩ / 1 kΩ  
- **Software** – **NI Multisim** for circuit simulation  

---

## Methodology

Each characteristic studied in the project follows a structured **three-step methodology**:

1. **Theoretical Solution**  
   Mathematical analysis and derivation of the underlying principles.

2. **Simulated Solution**  
   Verification of theoretical results using **Multisim** simulations and snapshots.

3. **Experimental Solution**  
   Physical implementation in the laboratory, including real-world measurements and observations.

---

## Key Findings (Example Data)

The **output characteristics** were recorded for various base current values (I<sub>b</sub>).  
For **I<sub>b</sub> = 75 mA**, the measured collector current values (I<sub>c</sub>) were:

- **V<sub>ce</sub> = 0.1 V** → I<sub>c</sub> = **13.2 mA**  
- **V<sub>ce</sub> = 0.6 V** → I<sub>c</sub> = **23.0 mA**  
- **V<sub>ce</sub> = 2.0 V** → I<sub>c</sub> = **23.4 mA**  
- **V<sub>ce</sub> = 9.0 V** → I<sub>c</sub> = **25.5 mA**

The **load line** was calculated using the equation:

$$
Vcc − Ic·Rc − Vce = 0
$$

This equation was used to determine the transistor’s **operating point (Q-point)**.

---

# Installation & Setup Guide  

This guide explains how to install, set up, and use the **BJT laboratory project** repository.  
The project focuses on the **common emitter BJT circuit**, combining **theoretical analysis**, **NI Multisim simulations**, and **experimental laboratory measurements**.

---

## Prerequisites

Before using this repository, ensure the following prerequisites are satisfied.

---

### 1. Software Requirements

#### NI Multisim
- **NI Multisim 14 or newer** (recommended)
- Required for:
  - Simulating common emitter BJT circuits
  - Plotting **input characteristics** (I<sub>b</sub>–V<sub>be</sub>)
  - Plotting **output characteristics** (I<sub>c</sub>–V<sub>ce</sub>)
  - Verifying theoretical load-line calculations

Used in:
- `lab1/MultisimPNG/`
- `lab3/MultisimPNG/`

---

#### PDF Reader
- Any modern PDF reader
- Required to open:
  - Assignment descriptions
  - Theoretical BJT documentation (English & Greek)

---

#### Image Viewer
- Any standard image viewer
- Required for viewing:
  - Lab photos
  - Simulation screenshots
  - Measurement graphs

---

### 2. Hardware Requirements (Optional – Physical Lab)

Only required if you want to **reproduce the experiments physically**.

- **Analog & Digital Training System:** MCP M21-7000A  
- **Digital Multimeter:** MCP MT8045  
- **DC Power Supply**
- **Components**
  - BJT transistor: **BC107BP**
  - Resistors: **560 Ω**, **10 kΩ**
  - Potentiometers: **100 kΩ**, **1 kΩ**
  - Breadboard & connecting wires

> Hardware is **not required** for theoretical study or Multisim simulations.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/BJT.git
cd BJT
```

### 2. Study the Theory
Navigate to the `docs/` directory and open:
- English: `Bipolar-Junction-Transistor.pdf`
- Greek: `Διπολικά-Τρανζίστορ.pdf`

These documents cover:
- BJT operation principles
- Common emitter configuration
- Input and output characteristics
- Load-line analysis and Q-point determination

### 3. Read the Assignment Instructions
Open the files in `assign/`:
- English: `Exercise-8th-Transistor.pdf`
- Greek: `Άσκηση-8η-Τρανζίστορ.pdf`

These define:
- Circuit configurations
- Measurement steps
- Required plots and calculations

### 4. Run Multisim Simulations
Input Characteristics (I<sub>b</sub> vs V<sub>be</sub>)
1. Launch NI Multisim.
2. Open the relevant circuit (or recreate it using the schematic from the PDFs).
3. Sweep V<sub>be</sub>.
4. Measure and plot base current (I<sub>b</sub>).

#### Output Characteristics (I<sub>c</sub> vs V<sub>ce</sub>)
1. Set fixed values of base current (I<sub>b</sub>).
2. Sweep V<sub>ce</sub>.
3. Record collector current (I<sub>c</sub>).
4. Compare simulation results with:
    - Theoretical curves
    - Experimental data in lab1/ and lab3/

### 5. Load Line & Q-Point Analysis
Use the equation:

$$
Vcc − Ic·Rc − Vce = 0
$$

Steps:
1. Determine `Vcc` and `Rc`.
2. Plot the load line on the I<sub>c</sub>–V<sub>ce</sub> graph.
3. Identify the operating point (Q-point).
4. Compare with:
    - Multisim results
    - Laboratory measurements

### 6. Review Experimental Results
- Experimental photos:
`lab1/LabPNG/`, `lab3/LabPNG/`
- Simulation screenshots:
`lab1/MultisimPNG/`, `lab3/MultisimPNG/`
- Notes & measurements:
`Notes/`

These materials validate:
- Agreement between theory, simulation, and practice
- Real-world effects such as transistor non-idealities
