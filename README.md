# CNT_MLIP
**Project Overview**

In this project, we developed MLIPs derived from ab initio MD (AIMD) trajectories. The MLIPs were trained using moment tensor potential (MTP) descriptors to ensure accurate representation of interatomic forces and energies.

This repository houses comprehensive datasets and resources related to our work on ab initio molecular dynamics and machine-learned interatomic potentials (MLIPs). Below is an overview of the contents:

AIMD Calculated Data: The results from AIMD simulations in cfg format.
Trained MLIPs: Machine-learned interatomic potentials optimized with the best set of hyperparameters.
VASP Input Scripts: Input scripts used for AIMD simulations include INCAR, POSCAR, and KPOINTS files.
LAMMPS MD Simulation Codes: Implemented MD simulation codes compatible with LAMMPS software.

**Application**

The performance of the developed MLIPs was evaluated through molecular dynamics simulations, specifically focusing on:

Stress-Strain Responses: Simulating the mechanical behavior of single-walled carbon nanotubes (SWCNTs) and defected SWCNTs (D-SWCNTs) under tensile loading conditions.

Our findings highlight the accuracy and efficiency of MLIPs in capturing the complex behaviors of carbon nanotubes, paving the way for advanced simulations in materials science.

**Repository Structure**

1_trained_MLIP/: Directory containing optimally trained MLIP potential.
2_Training_data/: Directory with cfg files containing AIMD. calculated data for different CNTs at different conditions for training and validation purposes.
3_VASP_ex/: VASP input scripts used for AIMD simulations.
4_MD_simulation: Implemented MD simulation codes for LAMMPS.
