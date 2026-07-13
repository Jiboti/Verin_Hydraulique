<h1 align="center">🔧 Vérin Hydraulique — Rotary Hydraulic Actuator</h1>
<h4 align="center">A Systems Engineering project — redesigning and optimizing a rotary hydraulic actuator for a teleoperated robotic arm — 

<p align="center">
  <img width="756" height="567" alt="image" src="https://github.com/user-attachments/assets/1568826a-62e1-4887-976f-f1cbb6e49b13" />
</p>

---

## 📋 Context — A Systems Engineering case study

This project applies a full **Systems Engineering** approach to a real industrial case. Acting as an engineering consultancy, our two-person team (Jaime Sousa & Antoine Roucault) answered a call for tender from **CYBERNETIX** — a Marseille-based company that designs rotary hydraulic actuators for manipulator arms operating in hostile environments — as part of a **Corporate Social Responsibility (CSR)** initiative.

These actuators equip the **MAESTRO** teleoperated arm, developed by the **CEA** (French Alternative Energies and Atomic Energy Commission) for **nuclear-dismantling** worksites, where radioactivity prevents human access. The mission: **rethink and optimize the actuator's design** to make it cheaper, more reliable and easier to maintain — without losing interchangeability with the existing fleet.

<p align="center">
  <img width="218" height="138" alt="image" src="https://github.com/user-attachments/assets/53a1fe50-52dc-4bb4-962e-14e2877ac945" />
</p>
<p align="center">
<img width="868" height="684" alt="image" src="https://github.com/user-attachments/assets/e27060aa-c7c5-4a8f-9191-1a9a51d94752" />
</p>


## 🎯 Objectives

The client's objectives, framed within the CSR approach, were to:

- **Standardize** the actuator's components and cut the number of part references,
- **Reduce** design time, fabrication time and cost,
- **Improve reliability** while keeping components interchangeable across the existing range,
- **Secure maintenance interventions** and lower their carbon footprint.

## 🧭 Method — RFLP, V-model & IVVQ

We followed the classic Systems Engineering framework: the **RFLP** flow (Requirements → Functions → Logical → Physical), structured within a **V-model** (*Cycle en V*), with **IVVQ** (Integration, Verification, Validation, Qualification) driving the test strategy.

The requirements analysis captured a demanding operating envelope: a **family of actuators covering 500–3000 Nm** of torque, fed with oil at **210 bar**, able to survive a hostile environment (high radiation, wide temperature range, operation underwater) and to stay within a strict size budget. These requirements drove every design choice that followed.

## 🔧 What we did

**Phase 1 — Parametric modeling in CATIA V5.**
We modeled the actuator's main parts — the **shaft** and the **central body** — assembled them, then made the assembly **fully parametric**: using CATIA's *Knowledge* features, the transmitted torque drives the key dimensions through formulas, so a single model can generate the whole family of actuators. This is where the **standardization** goal took shape — one bearing reference validated across all torque versions, with a justified safety factor.

<img width="975" height="698" alt="image" src="https://github.com/user-attachments/assets/8b1e47cf-8def-47b4-be30-7f84c8f29413" />
arbre

<img width="1248" height="487" alt="image" src="https://github.com/user-attachments/assets/8449041f-e131-4c8b-a443-1723533187df" />
corps central



**Phase 2 — Designing for lower fabrication cost.**
The original shafts used **monobloc vanes machined by electro-erosion** — precise, but slow and expensive. We studied a new solution: **removable reported vanes** (*palettes rapportées*) attached to the shaft and bore, positioned and held by **pins** (sized by shear) and **screws** (sized by the tightening cone). This cuts machining cost, eases maintenance, and keeps a clean standardization by part family. All sizing was backed by **strength-of-materials calculations and FEA** (CATIA **ELFINI**), consolidated in **Excel** computation tables.

<p align="center">
<img width="336" height="429" alt="image" src="https://github.com/user-attachments/assets/b6eb3108-96f5-4c81-acfb-cc62946bd415" />
</p>

## 📈 Results

The technical model met the client's brief: a **standardized family of parts**, a **single bearing reference** validated for a **1000 h** service life before maintenance, and a **justified safety factor** for each torque version — all while reducing fabrication cost through the removable-vane solution, and preserving interchangeability with the existing actuators. The proposal was validated by the client.

On a personal note, this project was my first real hands-on dive into **CATIA V5** and into a structured Systems Engineering process — a demanding but formative combination.

<p align="center">
  <img width="300" height="240" alt="image" src="https://github.com/user-attachments/assets/2be562f0-d302-4c07-9cf0-ab67c8e2db98" />

</p>

## 🛠️ Tools & technologies

`CATIA V5` (Part Design · Assembly · Knowledge · ELFINI FEA) · `Excel`

---

<p align="center"><a href="https://github.com/Jiboti">⬅️ Back to profile</a></p>
