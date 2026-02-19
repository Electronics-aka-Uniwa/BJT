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

# README

## Bipolar Junction Transistor (BJT)

This repository contains the laboratory report for **Project 5**, focusing on the study and analysis of a **Bipolar Junction Transistor (BJT)** operating in a **common emitter circuit configuration**. The project combines **theoretical calculations**, **software simulations**, and **experimental laboratory measurements**.

---

## Table of Contents

| Section | Folder / File                          | Description                                                  |
| ------: | -------------------------------------- | ------------------------------------------------------------ |
|       1 | `assign/`                              | Assignment material                                          |
|     1.1 | `assign/Exercise-8th-Transistor.pdf`   | Assignment description (English)                             |
|     1.2 | `assign/Άσκηση-8η-Τρανζίστορ.pdf`      | Assignment description (Greek)                               |
|       2 | `docs/`                                | Theoretical documentation                                    |
|     2.1 | `docs/Bipolar-Junction-Transistor.pdf` | BJT theory (English)                                         |
|     2.2 | `docs/Διπολικά-Τρανζίστορ.pdf`         | BJT theory (Greek)                                           |
|       3 | `lab1/LabPNG/`                         | Lab 1 experimental images                                    |
|     3.1 | `lab1/MultisimPNG/`                    | Lab 1 Multisim simulation images                             |
|       4 | `lab3/LabPNG/`                         | Lab 3 experimental images                                    |
|     4.1 | `lab3/MultisimPNG/`                    | Lab 3 Multisim simulation images                             |
|     4.2 | `lab3/3a.jpg`                          | Lab 3 additional image                                       |
|       5 | `LabPNG/`                              | General lab images and setups                                |
|       6 | `Notes/`                               | Notes, extra images, measurement screenshots, and data files |
|       7 | `README.md`                            | Repository overview and instructions                         |

---

## 1. Project Contents

The report is structured into key sections centered on the **Common Emitter Circuit**:

- **Output Characteristics (I<sub>c</sub> = f(V<sub>ce</sub>))**  
  Detailed analysis of collector current versus collector–emitter voltage  
  _(Pages 6–33)_

- **Input Characteristics (I<sub>b</sub> = f(V<sub>be</sub>))**  
  Analysis of base current versus base–emitter voltage  
  _(Pages 34–57)_

- **Laboratory Questions**  
  Analytical responses to experiment-related questions  
  _(Pages 58–59)_

---

## 2. Equipment and Components

The following equipment and components were used during the experimental phase:

- **MCP M21-7000A** – Analog & Digital Training System (Breadboard)
- **MCP MT8045** – Digital Multimeter Bench
- **Transistor** – BJT **BC107BP**
- **Resistors** – 560 Ω, 10 kΩ
- **Potentiometers** – 100 kΩ / 1 kΩ
- **Software** – **NI Multisim** for circuit simulation

---

## 3. Methodology

Each characteristic studied in the project follows a structured **three-step methodology**:

1. **Theoretical Solution**  
   Mathematical analysis and derivation of the underlying principles.

2. **Simulated Solution**  
   Verification of theoretical results using **Multisim** simulations and snapshots.

3. **Experimental Solution**  
   Physical implementation in the laboratory, including real-world measurements and observations.

---

## 4. Key Findings (Example Data)

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
