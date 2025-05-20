
# Optimization of Outpatient Clinic Processes through Simulation

> Mownika Konamaneni. 

Learn more about me in my [GitHub profile page](https://github.com/MownikaKonamaneni). 


The following is a project created during the _"Optimization and Simulation"_ course.

This project investigates ways to improve the operational efficiency of an outpatient clinic using **discrete-event simulation modeling** in **SIMUL8**. The study focuses on reducing patient wait times, improving resource utilization, and analyzing financial performance through a data-driven simulation approach.

---

## 📘 Introduction

Outpatient clinics often face challenges such as long patient wait times, inefficient resource use, and administrative bottlenecks. This project simulates and analyzes the full patient journey—from registration to checkout—to uncover actionable improvements in clinic performance and patient satisfaction.

---

## 📁 Project Structure


```
📁 Optimization and Simulation
├── 📦 Simulation Project/
│   ├── FinalProject_Phase1.s8
|   ├── FinalProject_Phase2.s8
│
├── 📁 Literature Review/
│   └── ESI 5315-Optimization and Simulation-Taj-SP23 R_1_24_23.pdf
│
├── 📁 Presentation/
│   └── Optimization of Outpatient Clinic Processes through simulation.pptx
│
├── 📁 Project Reports/
│   └── Project Report.docx
│
└── README.md

```
---

## 🔬 Methodology
### Phase I – Current Process Analysis
* Simulated clinic processes: registration, waiting, nurse interview, MD exam, lab/EKG, checkout.
* Collected time and arrival data, used probability distributions:
  * Exponential, Lognormal, Triangular
* Analyzed KPIs:
  * Average wait time: 2.9 hours
  * Total time in clinic: 3.52 hours
  * Identified staffing insufficiencies and process delays

### Phase II – Financial Analysis & Resource Optimization
* Introduced:
  * Multiple checkout points
  * Morning & afternoon shift allocations
* Generated income statements for revenue and expense evaluation
* Optimized staffing:
  * 1 Registrar, 2 Nurses, 3 Doctors, 1 Bookkeeper
---

## 📊 Key Findings
* Only 5% of patients finish in 1 hour
* Phase I average total clinic time: 211.72 mins (3.52 hrs)
* Phase II results:
  * Lab patients: 1.95 hrs
  * Doctor-only patients: 2.6 hrs
  * Optimal configuration improves throughput and reduces idle time
---

## ✅ Recommendations
* Use self-service registration kiosks
* Adjust staff allocation during peak hours
* Implement appointment-based scheduling
---

## 💻 Tools & Technologies
* SIMUL8 – Discrete-event simulation
* Microsoft Excel – Financial modeling

---

## 📄 Reference
Taj, S. and Mousavidin, E. (2015). Using discrete event visual simulation to teach process modelling in MBA operations management courses, Int. J. Simulation and Process Modelling, 10(1).
