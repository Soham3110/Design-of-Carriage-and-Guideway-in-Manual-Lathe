# 🛠️ Lathe Carriage, Guideways & Lead Screw Structural Design and Simulation
---

## 📌 Project Overview

This project focuses on the **design, structural analysis, and simulation of a manual lathe machine’s carriage, guideways, and lead screw system** — core components responsible for precise tool positioning during machining.  

Our goal was to understand how these elements behave under actual machining forces (cutting forces, weight, reaction moments) and ensure that they meet safety and functional standards through both analytical and simulation-based validations.

This included:
- Deriving load equilibrium conditions  
- Calculating contact and axial forces  
- Assessing stress concentration at guideway junctions  
- Designing a lead screw resistant to both torsional and buckling failure  
- Validating the entire system using SolidWorks static and buckling simulations  
- Cross-verifying calculations with custom MATLAB scripts  

---

## 📐 Why This Matters

In any lathe machine, ensuring the **carriage and lead screw assembly can withstand cutting loads without excessive deformation or buckling is essential** for precision and operator safety. 

This project replicates real-world design decision-making — combining material selection, dimensioning, stress analysis, and simulation — reflecting practical mechanical engineering challenges.

---

## 📊 Project Breakdown

### 🔧 Components Designed & Analyzed
- **Carriage**: Supports tool post, compound rest, and cross-slide; designed for optimal stiffness.
- **Guideways**: Ensures smooth, accurate carriage motion while withstanding reaction and cutting forces.
- **Lead Screw**: Transmits motion to the carriage; designed for torsional and buckling resistance.
- **Lathe Bed, Tool Holder, Cutting Tool**: Modeled for completeness and load distribution accuracy.

---

## 📏 Key Design Parameters

| Parameter         | Value / Range |
|:-----------------|:---------------|
| Carriage weight    | 2000 N         |
| Cutting forces (Fx, Fy, Fz) | (500 N, 800 N, 4000 N) |
| Bed length         | 0.76 m         |
| Lead screw lead    | 3.175 mm       |
| Contact angle      | 45°            |
| Friction coefficient | 0.1          |

---

## 📝 What We Did

✔️ Developed 3D models for the carriage, guideways, lead screw, and associated parts in **SolidWorks**  
✔️ Derived force equilibrium relations to compute contact forces at guideways (F1, F2, F3)  
✔️ Analyzed notch stresses and stress concentration factors at the V-guide junction  
✔️ Designed lead screw dimensions based on:
- Torsional strength (from cutting forces and torque requirement)
- Buckling resistance (using Euler’s theory with fixed–fixed end conditions)
✔️ Wrote custom **MATLAB scripts** to compute analytical values for:
- Normal forces  
- Lead screw safe diameters under torsion and buckling  
- Factor of safety for each component  
✔️ Ran **SolidWorks simulations** for:
- Static stress analysis  
- Buckling analysis of the lead screw under axial loads  

---

## 📐 Materials Used and Why

| Component       | Material            | Why We Chose It |
|:----------------|:-------------------|:----------------------------------------------------------|
| Lathe Bed        | FG200 (Grey Cast Iron) | Great vibration damping and compressive strength |
| Carriage & Guideways | FG260 (High-Grade Cast Iron) | Higher hardness, wear resistance, and sliding properties |
| Lead Screw       | ANSI 1045 (Medium Carbon Steel) | Good tensile strength and machinability |
| Tool Holder      | Cast Alloy Steel     | High toughness and wear resistance under cutting loads |
| Cutting Tool     | HSS (High-Speed Steel) | Retains hardness at elevated temperatures |

---

## 📊 Simulation Highlights  

- **Static analysis** verified that stresses remain within allowable limits under operational loads.
- **Buckling analysis** confirmed the selected lead screw diameter is safe against axial compression.
- Maximum observed deflection and stress values from the simulation matched analytical predictions closely.

---

## 📊 Final Design Outcome  

- **Lead screw safe diameter**:
  - Torsion: 7.7 mm  
  - Buckling: 15 mm  
  - Final chosen: 20 mm (with safety factor)  
- **Guideway-contact normal forces** computed for cutting and reaction conditions  
- **Carriage structure verified for both static and dynamic stability**

---

## 📚 Tools & Technologies

- 📐 SolidWorks (3D Modeling, Static, Fattigue & Buckling Simulation)
- 📊 MATLAB (Analytical Calculations, Design Verification)
- 📝 Structural Mechanics, Machine Design Principles

---

## 📸 Project Gallery  
- `lathe_assembly.png`
  ![lathe_assembly](https://github.com/user-attachments/assets/84d39123-44f0-44a8-9345-128bb1f90f7d)
- `Stress.png`
![Stress](https://github.com/user-attachments/assets/769c287b-94f3-40c1-813b-c8024df8640e)
- `Displacement.png`
![Displacement](https://github.com/user-attachments/assets/d1d1e065-1a4c-4115-b639-84720cb1b43a)
- `Strain.png`
![Strain](https://github.com/user-attachments/assets/e5d1e50c-9289-4674-95c2-dc4881dac709)
- `buckling_simulation.png`
![buckling_simulation](https://github.com/user-attachments/assets/aaf2359d-4635-4582-8749-5e15faf45293)

---

## 🚀 Future Work  

- Extend the design for CNC automation integration  
- Perform full dynamic FEA under real cutting cycles  
- Optimise material selection based on cost-performance trade-offs  
- Develop a digital twin prototype of the entire lathe assembly  

---

## 📞 Contact  

For queries, ideas, or collaboration:
- Yogesh
- Sonal : sonalraj8453@gmail.com
- Or open an issue on this repository.

---

