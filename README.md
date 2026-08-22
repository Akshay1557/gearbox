4-Gear Gearbox Design & Kinematic Simulation – CATIA V5
Project Overview

This project is a 3D CAD model and kinematic simulation of a 4-gear gearbox developed using CATIA V5.

The gearbox consists of four spur gears mounted on three shafts, supported by bearings and assembled on a gearbox housing. The assembly was developed using CATIA V5 Assembly Design and its motion was studied using the DMU Kinematics workbench.

Components
4 Spur Gears
3 Shafts
6 Bearings
Gearbox Housing/Base
Assembly Constraints
Revolute Joints
Gear Joints
Gear Configuration

The gearbox uses the following gear arrangement:

20T → 50T → 20T → 50T

The second shaft carries two gears and transfers motion from the first shaft to the third shaft.

Gear Ratio

For the first gear pair:

Ratio=
50
20
	​

=0.4

For the second gear pair:

Ratio=
50
20
	​

=0.4

Therefore, the overall speed ratio is:

0.4×0.4=0.16

This means the output shaft rotates at approximately 16% of the input shaft speed, with the output direction being the same as the input direction.

CATIA V5 Workbenches Used
Part Design – Component modelling
Assembly Design – Gearbox assembly and constraints
DMU Kinematics – Revolute joints, gear joints and motion simulation
Kinematic Setup

Three revolute joints were created for the three shafts:

Revolute.1 → Shaft 1
Revolute.2 → Shaft 2
Revolute.3 → Shaft 3

Two gear relationships were created:

Gear Joint 1: Revolute.1 ↔ Revolute.2, Ratio = 0.4, Opposite direction
Gear Joint 2: Revolute.2 ↔ Revolute.3, Ratio = 0.4, Opposite direction
Project Workflow
Model individual gears
Model shafts and bearings
Model gearbox housing
Assemble all components
Apply assembly constraints
Create revolute joints
Create gear joints
Define gear ratios
Apply input rotation command
Perform DMU Kinematics simulation


Software
CATIA V5

Learning Outcomes

This project helped develop practical skills in:

3D CAD modelling,
Mechanical assembly,
Spur gear design,
Assembly constraints,
Shaft and bearing arrangement,
Gear ratio calculation,
DMU Kinematics,
Revolute and Gear Joints,
Mechanical motion simulation,
Project Status

Completed: 3D modelling, assembly and kinematic mechanism development.

Future Work: Further refinement of gear-to-shaft connections and advanced mechanical/FEA analysis.
