# Delft3D_AdaptiveCalib_MOR
Delft3D Adaptive Calibration for Morphodynamic Simulation — Noshahr Beach (Caspian Sea)

This repository contains all model setup files used in the study:

“Improving the Simulation of Seasonal Beach Profile Evolution Through Adaptive Calibration of the Delft3D Model.”

The repository includes complete Delft3D configuration files needed to reproduce :

The real-world field application for Noshahr Beach (Caspian Sea).

🔹 Repository Contents
1. Delft3D Model Setup Files

These files are fully ready for execution in Delft3D:

*.mdf — FLOW input file

*.mdw — WAVE input file

*.bnd — boundary condition file

*.ini — initial condition file

*.dep — bathymetry grid

*.grd — horizontal grid

Note:
The raw ADCP and survey datasets are copyrighted by Mahmoudof & Takami (2022) and cannot be redistributed.
Only the processed datasets used directly in the model simulations are included here.

🔹 How to Run the Model

Open Delft3D (Delft3D-FLOW and Delft3D-WAVE).

Load the *.mdf file for FLOW.

Load the *.mdw file for WAVE.

Ensure that relative paths to boundary files and grids remain unchanged.

Enable two-way online coupling (as used in the study).

Run FLOW → WAVE and allow automatic coupling every 12 minutes.

The setup reproduces:

Field Case Application (Noshahr Beach)

Real storm event: 15–20 November 2014

Adaptive calibration based on the Hattori–Kawamata criterion

🔹 Citation

If you use this repository, please cite the published article:

Khosh Kholgh, A. et al. (2025). Improving the Simulation of Seasonal Beach Profile Evolution Through Adaptive Calibration of the Delft3D Model. Marine Geology.

🔹 Contact

For questions, feel free to contact:

Ali Khosh Kholgh
Email: a_khosh@inio.ac.ir
