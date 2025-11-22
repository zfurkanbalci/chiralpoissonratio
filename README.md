# chiralpoissonratio
This repository contains the FEA-generated datasets of a chiral auxetic mechanical metamaterial for mesh sensitivity analysis (0.2 mm, 0.25 mm, 0.3 mm). All data were produced by the authors to ensure transparency, reproducibility, and support further research on Poisson’s ratio prediction.

📂 Chiral Auxetic Metamaterial Dataset (Mesh Sensitivity – 0.2 mm / 0.25 mm / 0.3 mm)

This repository contains the finite element analysis (FEA) datasets generated for the study:
“A Hybrid Grey Wolf Optimizer–XGBoost Framework for Modelling the Poisson’s Ratio of Mechanical Metamaterials.”
The data were produced entirely by the authors and are publicly shared to ensure transparency, reproducibility, and reusability for future research.

📘 Dataset Description

The dataset includes numerical results from FEA simulations conducted on a chiral auxetic mechanical metamaterial unit cell. To evaluate mesh sensitivity and ensure mesh independence, three different element sizes were used:
0.20 mm
0.25 mm
0.30 mm
Each Excel file contains the complete output of the FEA simulations performed under identical boundary conditions, with only the mesh size varied. The results include deformation-based Poisson’s ratio calculations and other response quantities derived from the simulations.

📁 Files Included
File Name	Description
CChiral Veri Seti 20.09.2025 – 0.2 Mesh.xlsx	FEA results for mesh size = 0.20 mm
CChiral Veri Seti 20.09.2025 – 0.25 Mesh.xlsx	FEA results for mesh size = 0.25 mm
CChiral Veri Seti 20.09.2025 – 0.3 Mesh.xlsx	FEA results for mesh size = 0.30 mm

All files contain the same variable structure and column definitions, enabling direct comparison across mesh sizes.

🧪 Methodology Summary
Geometry: Chiral auxetic unit cell
Software: ANSYS Mechanical (FEA)
Analysis Type: Static structural
Boundary Conditions: Fixed/loaded edges applied consistently across all meshes
Output Metric: Poisson’s ratio calculated from resulting deformations
Purpose: To validate mesh independence and determine the most efficient element size for accurate predictions
These datasets support the mesh convergence analysis presented in the manuscript.

🔄 Reproducibility

Researchers can:
Reproduce mesh sensitivity plots
Validate model convergence
Use the dataset to train/benchmark machine learning models
Compare FEA results across different solvers or mesh strategies
The dataset is provided without restrictions for academic and research use.

📬 Contact

For questions or collaboration requests, please contact the authors:


Lecturer Hümeyra Şevval Balcı
Email: humeyrasevval.balci@yuksekihtisas.edu.tr

Lecturer Furkan Balcı
Email: furkanbalci@gazi.edu.tr
