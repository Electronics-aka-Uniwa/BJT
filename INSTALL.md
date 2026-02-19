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

<hr>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Panagiotis Giannakopoulos, Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/panagiotis-yannakopoulos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/panos-yannakopoulos-b9b6987/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Academic Scholar
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/academic_sc_ho/" target="_blank">UNIWA Profile</a> ·
  <a href="https://scholar.google.com/citations?user=-LnaZGgAAAAJ&hl=en" target="_blank">Scholar</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

</hr>

---

<p align="center">
  Athens, January 2023
</p>

---

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4mMEQ-cD4FZhvoYeIgl2x4p3IxozlkM5Nxw&s" width="250"/>
</p>

---

# INSTALL

## Bipolar Junction Transistor (BJT)

This guide explains how to install, set up, and use the **BJT laboratory project** repository.  
The project focuses on the **common emitter BJT circuit**, combining **theoretical analysis**, **NI Multisim simulations**, and **experimental laboratory measurements**.

---

## 1. Prerequisites

Before using this repository, ensure the following prerequisites are satisfied.

---

## 2. Software Requirements

### 2.1 NI Multisim

- **NI Multisim 14 or newer** (recommended)
- Required for:
  - Simulating common emitter BJT circuits
  - Plotting **input characteristics** (I<sub>b</sub>–V<sub>be</sub>)
  - Plotting **output characteristics** (I<sub>c</sub>–V<sub>ce</sub>)
  - Verifying theoretical load-line calculations

Used in:

- `lab1/MultisimPNG/`
- `lab3/MultisimPNG/`

### 2.2 PDF Reader

- Any modern PDF reader
- Required to open:
  - Assignment descriptions
  - Theoretical BJT documentation (English & Greek)

### 2.3 Image Viewer

- Any standard image viewer
- Required for viewing:
  - Lab photos
  - Simulation screenshots
  - Measurement graphs

---

## 3. Hardware Requirements

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

## 4. Installation & Setup

### 4.1 Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/BJT.git
cd BJT
```

### 4.2 Study the Theory

Navigate to the `docs/` directory and open:

- English: `Bipolar-Junction-Transistor.pdf`
- Greek: `Διπολικά-Τρανζίστορ.pdf`

These documents cover:

- BJT operation principles
- Common emitter configuration
- Input and output characteristics
- Load-line analysis and Q-point determination

### 4.3 Read the Assignment Instructions

Open the files in `assign/`:

- English: `Exercise-8th-Transistor.pdf`
- Greek: `Άσκηση-8η-Τρανζίστορ.pdf`

These define:

- Circuit configurations
- Measurement steps
- Required plots and calculations

### 4.4 Run Multisim Simulations

Input Characteristics (I<sub>b</sub> vs V<sub>be</sub>)

1. Launch NI Multisim.
2. Open the relevant circuit (or recreate it using the schematic from the PDFs).
3. Sweep V<sub>be</sub>.
4. Measure and plot base current (I<sub>b</sub>).

### 4.5 Output Characteristics (I<sub>c</sub> vs V<sub>ce</sub>)

1. Set fixed values of base current (I<sub>b</sub>).
2. Sweep V<sub>ce</sub>.
3. Record collector current (I<sub>c</sub>).
4. Compare simulation results with:
   - Theoretical curves
   - Experimental data in lab1/ and lab3/

### 4.6 Load Line & Q-Point Analysis

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

### 4.7 Review Experimental Results

- Experimental photos:
  `lab1/LabPNG/`, `lab3/LabPNG/`
- Simulation screenshots:
  `lab1/MultisimPNG/`, `lab3/MultisimPNG/`
- Notes & measurements:
  `Notes/`

These materials validate:

- Agreement between theory, simulation, and practice
- Real-world effects such as transistor non-idealities
