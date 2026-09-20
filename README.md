# Multi-Stage Gearbox Design & Motion Simulation using CATIA V5

## 📌 Project Overview

This project presents the complete **3D CAD design, assembly, and kinematic simulation of a two-stage spur gear reduction gearbox using CATIA V5**.

The gearbox consists of **three shafts and four spur gears** arranged in two reduction stages. The individual components, including gears, shafts, bearings, keyways, gearbox housing, and gearbox cover, were designed and assembled in CATIA V5.

The completed gearbox assembly was constrained and simulated using **CATIA V5 DMU Kinematics** to demonstrate gear interaction, shaft rotation, and speed reduction.

---

## 🎯 Project Objectives

- Design a complete two-stage spur gear reduction gearbox.
- Model individual gears, shafts, bearings, and housing components.
- Calculate gear ratios, speed reduction, and theoretical torque transmission.
- Design and integrate keyways between gears and shafts.
- Design the complete gearbox housing and cover.
- Assemble all components using CATIA V5 Assembly Design.
- Apply assembly constraints and mechanical joints.
- Establish gear mechanisms for power transmission.
- Perform kinematic motion simulation using DMU Kinematics.
- Prepare final engineering drawings of the gearbox components.
- Develop complete project documentation.

---

## 🛠️ Software Used

- **CATIA V5**
  - Sketcher
  - Part Design
  - Assembly Design
  - DMU Kinematics
  - Drafting

---

# ⚙️ Gearbox Configuration

The gearbox consists of four spur gears mounted on three shafts.

| Gear | Teeth | Module | Pressure Angle | Pitch Diameter | Outside Diameter | Root Diameter |
|------|------:|-------:|---------------:|---------------:|-----------------:|--------------:|
| G1 | 20T | 4 mm | 20° | 80 mm | 88 mm | 70 mm |
| G2 | 50T | 4 mm | 20° | 200 mm | 208 mm | 190 mm |
| G3 | 20T | 4 mm | 20° | 80 mm | 88 mm | 70 mm |
| G4 | 40T | 4 mm | 20° | 160 mm | 168 mm | 150 mm |

The 20-tooth gear drawing specifies a module of 4 mm, 20° pressure angle, 80 mm pitch diameter, 88 mm outside diameter, and 70 mm root diameter. :chatgpt-content-reference{index="3"}

The 40-tooth gear drawing specifies a module of 4 mm, 20° pressure angle, 160 mm pitch diameter, 168 mm outside diameter, and 150 mm root diameter. :chatgpt-content-reference{index="4"}

The 50-tooth gear drawing specifies a module of 4 mm, 20° pressure angle, 200 mm pitch diameter, 208 mm outside diameter, and 190 mm root diameter. :chatgpt-content-reference{index="5"}

---

# 🔄 Gear Arrangement

The power transmission sequence is:

```text
                  TWO-STAGE GEARBOX

                       INPUT
                         │
                         ▼
                   Input Shaft
                         │
                         ▼
                     G1 (20T)
                         │
                         ▼
                     G2 (50T)
                         │
                         ▼
                Intermediate Shaft
                         │
                         ▼
                     G3 (20T)
                         │
                         ▼
                     G4 (40T)
                         │
                         ▼
                   Output Shaft
                         │
                         ▼
                       OUTPUT
G1 and G2 form the first reduction stage, while G3 and G4 form the second reduction stage.
📐 Gear Specifications
G1 and G3 — 20-Tooth Gear
Parameter	Value
Number of Teeth	20
Module	4 mm
Pitch Diameter	80 mm
Pitch Radius	40 mm
Pressure Angle	20°
Addendum	4 mm
Dedendum	5 mm
Whole Depth	9 mm
Outside Diameter	88 mm
Root Diameter	70 mm
Base Circle Diameter	75.18 mm
Circular Pitch	12.57 mm
Tooth Thickness	6.28 mm
Clearance	1 mm
Angular Pitch	18°


G2 — 50-Tooth Gear
Parameter	Value
Number of Teeth	50
Module	4 mm
Pitch Diameter	200 mm
Pitch Radius	100 mm
Pressure Angle	20°
Addendum	4 mm
Dedendum	5 mm
Whole Depth	9 mm
Outside Diameter	208 mm
Root Diameter	190 mm
Circular Pitch	12.57 mm
Tooth Thickness	6.28 mm
Clearance	1 mm
Angular Pitch	7.2°


Note: The 50T gear drawing does not specify a base-circle diameter, so it is not included in the table.

G4 — 40-Tooth Gear
Parameter	Value
Number of Teeth	40
Module	4 mm
Pitch Diameter	160 mm
Pitch Radius	80 mm
Pressure Angle	20°
Addendum	4 mm
Dedendum	5 mm
Whole Depth	9 mm
Outside Diameter	168 mm
Root Diameter	150 mm
Base Circle Diameter	150.35 mm
Circular Pitch	12.57 mm
Tooth Thickness	6.28 mm
Clearance	1 mm
Angular Pitch	9°


📊 Gear Ratio Calculation
The gearbox uses two reduction stages.
Stage 1 — G1 to G2
G1 = 20 teeth
G2 = 50 teeth
R₁ = T₂ / T₁

R₁ = 50 / 20

R₁ = 2.5
Therefore:
Stage 1 reduction = 2.5 : 1
Stage 2 — G3 to G4
G3 = 20 teeth
G4 = 40 teeth
R₂ = T₄ / T₃

R₂ = 40 / 20

R₂ = 2
Therefore:
Stage 2 reduction = 2 : 1
Overall Reduction Ratio
Rₜ = R₁ × R₂

Rₜ = 2.5 × 2

Rₜ = 5
Total Reduction Ratio
5 : 1
The theoretical analysis for the gearbox also specifies a 5:1 total reduction based on the 2.5:1 and 2:1 stages. theoretical-analysis
🌀 Speed Analysis
The theoretical input speed is:
1500 rpm
The theoretical output speed is:
Output Speed = Input Speed / Total Reduction Ratio

Output Speed = 1500 / 5

Output Speed = 300 rpm
Parameter	Value
Input Speed	1500 rpm
Total Reduction Ratio	5:1
Theoretical Output Speed	300 rpm


🔧 Torque Analysis
The theoretical motor output torque is:
8.82 Nm
The calculated shaft torque values are:
Shaft	Torque
Input Shaft	8.82 Nm
Intermediate Shaft	22.05 Nm
Output Shaft	44.10 Nm


The theoretical analysis calculates the intermediate and output shaft torque using the respective reduction ratios. theoretical-analysis
🔩 Main Components
The completed gearbox consists of:
Shafts
- Input Shaft
- Intermediate Shaft
- Output Shaft
Gears
- G1 — 20T
- G2 — 50T
- G3 — 20T
- G4 — 40T
Supporting Components
- Bearings
- Keys
- Keyways
- Gearbox Housing
- Gearbox Cover
- Fasteners
🏗️ Gearbox Housing
A complete gearbox housing was designed in CATIA V5 to support and enclose the internal components.
The housing provides:
- Support for shafts and bearings
- Gear protection
- Shaft alignment
- Structural support
- Mounting provisions
- Enclosure for the gearbox mechanism
A separate gearbox cover was also designed and integrated with the housing during assembly.
⚙️ Bearing Arrangement
Bearings were incorporated into the gearbox assembly to support the rotating shafts and maintain shaft alignment.
The bearing arrangement provides:
- Radial support for the shafts
- Proper shaft positioning
- Reduced friction during rotation
- Stable gear alignment
- Support for the rotating assembly
🔑 Shaft and Keyway Design
Keyways were incorporated into the shaft and gear connection to transmit rotational torque between the shafts and gears.
The keyway arrangement ensures that the gears rotate together with their respective shafts during the kinematic simulation.
🧩 Assembly Design
All individual components were assembled using CATIA V5 Assembly Design.
The completed assembly includes:
- Three shafts
- Four gears
- Bearings
- Keys and keyways
- Gearbox housing
- Gearbox cover
- Supporting components
Assembly constraints were applied to correctly position and align the components.
🔗 Assembly Constraints
Appropriate CATIA V5 assembly constraints were applied to:
- Position shafts
- Align bearings
- Position gears on shafts
- Maintain gear alignment
- Position the gearbox housing
- Fix stationary components
- Maintain the required relationships between rotating components
These constraints were used to create a functional gearbox assembly suitable for kinematic simulation.
🔄 Gear Mechanism
The gear mechanism was created to establish the rotational relationship between the mating gears.
The gearbox contains two gear pairs:
G1 (20T) ↔ G2 (50T)

G3 (20T) ↔ G4 (40T)
The gear ratios define the speed relationship between the mating gears.
🎥 DMU Kinematic Simulation
The completed gearbox was simulated using CATIA V5 DMU Kinematics.
The simulation demonstrates:
- Input shaft rotation
- G1 rotation
- G2 rotation
- Intermediate shaft rotation
- G3 rotation
- G4 rotation
- Output shaft rotation
- Gear interaction
- Speed reduction
The kinematic mechanism allows the rotational motion of the gearbox to be visualized as a complete assembly.
📐 Engineering Drawings
Final engineering drawings were prepared for the designed gearbox components.
The drawings include relevant:
- Component dimensions
- Gear specifications
- Views
- Sectional details where required
- Manufacturing dimensions
- Component identification
The drawings provide technical documentation of the CAD models.
🧱 Material Selection
Gears
Material: AISI 1045 Steel, Cold Drawn
The selected gear material provides a balance of:
- Strength
- Hardness
- Cost-effectiveness
- Manufacturability
Gearbox Housing
Material: Aluminum Alloy 6061-T6
The selected housing material provides:
- Low weight
- Good thermal conductivity
- Good machinability
- Suitable properties for the housing application
These material selections are specified in the theoretical analysis prepared for the project. theoretical-analysis
🛠️ Project Workflow
Gearbox Concept
      ↓
Gear Ratio Calculation
      ↓
Gear Dimension Calculation
      ↓
Gear Modeling
      ↓
Input Shaft Design
      ↓
Intermediate Shaft Design
      ↓
Output Shaft Design
      ↓
Keyway Design
      ↓
Bearing Arrangement
      ↓
Gearbox Housing Design
      ↓
Gearbox Cover Design
      ↓
Complete Assembly
      ↓
Assembly Constraints
      ↓
Gear Mechanism
      ↓
DMU Kinematics
      ↓
Motion Simulation
      ↓
Engineering Drawings
      ↓
Final Documentation
📊 Project Parameters
Parameter	Value
Gear Type	Spur Gear
Number of Gears	4
Number of Shafts	3
Module	4 mm
Pressure Angle	20°
Total Reduction Ratio	5:1
Input Speed	1500 rpm
Theoretical Output Speed	300 rpm
CAD Software	CATIA V5
Kinematic Simulation	DMU Kinematics
Project Status	Completed


💡 Skills Demonstrated
- Mechanical Design
- 3D CAD Modeling
- CATIA V5
- CATIA Sketcher
- CATIA Part Design
- CATIA Assembly Design
- CATIA DMU Kinematics
- Spur Gear Design
- Gear Ratio Calculation
- Torque Calculation
- Shaft Design
- Bearing Arrangement
- Keyway Design
- Gearbox Housing Design
- Assembly Constraints
- Mechanical Assembly
- Engineering Drawing
- Kinematic Motion Simulation
- Technical Documentation
✅ Project Completion Status
The complete gearbox project has been successfully modeled, assembled, and documented in CATIA V5.
Completed Components and Tasks
- [x] Gear ratio calculations
- [x] 20T gear design
- [x] 50T gear design
- [x] 40T gear design
- [x] Input shaft
- [x] Intermediate shaft
- [x] Output shaft
- [x] Keyway design
- [x] Bearing arrangement
- [x] Complete gearbox housing
- [x] Gearbox cover
- [x] Complete gearbox assembly
- [x] Assembly constraints
- [x] Gear mechanism
- [x] DMU Kinematic simulation
- [x] Final engineering drawings
- [x] Final documentation
🎯 Final Outcome
The completed project demonstrates the design and virtual operation of a two-stage spur gear reduction gearbox using CATIA V5.
The project demonstrates:
- Mechanical power transmission
- Two-stage speed reduction
- Gear interaction
- Shaft rotation
- Torque transmission
- Bearing-supported shaft arrangement
- Mechanical assembly
- Gearbox housing design
- Assembly constraints
- Kinematic motion simulation
- Engineering documentation
The theoretical gearbox provides an overall 5:1 reduction, corresponding to a theoretical reduction from 1500 rpm input speed to 300 rpm output speed.
📚 Project Domain
Mechanical Design | CAD Modeling | Gearbox Design | Mechanical Assembly | Kinematic Simulation
👨‍💻 Author
Mechanical Engineering Student

