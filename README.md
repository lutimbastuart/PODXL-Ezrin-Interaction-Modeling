# PODXL-Ezrin-Interaction-Modeling
Computational modeling and virtual screening study elucidating the structural dynamics of Podocalyxin (PODXL)-Ezrin interactions, with a focus on the R495W mutation's role in cancer metastasis. Includes docked models, MD simulation trajectories, and hit compounds for therapeutic targeting.



## Overview
This repository accompanies the manuscript **"Structural and Dynamic Insights into Podocalyxin-Ezrin Interaction as a Target in Cancer Progression"** by Mila Milutinovic, Stuart Lutimba, and Mohammed A. Mansour (London South Bank University, 2025). 

The study employs an integrated computational pipeline including protein-protein docking (HADDOCK 2.4), molecular dynamics (MD) simulations (OpenMM 8.1.2 & GROMACS 2024.2), and virtual screening (AutoDock 4.2.6) to characterize the PODXL-Ezrin interface. Key contributions:
- **Structural Modeling**: AlphaFold-predicted full-length models of PODXL (residues 322–558) and Ezrin, with stereochemical validation via Ramachandran plots.
- **Mutation Analysis**: Impact of the clinically relevant R495W mutation in PODXL's cytoplasmic domain, revealing allosteric destabilization of Ezrin's dormant state (e.g., increased F3-C-terminal distance from 2.59 Å to 3.40 Å).
- **Dynamic Insights**: 100 ns MD for wild-type (WT) and 20 ns for mutant complexes, showing enhanced rigidity (RMSD: 10.30 Å vs. 12.08 Å) and pre-C-terminal loop engagement in the mutant.
- **Therapeutic Hits**: Virtual screening of an in-house library (>2019 compounds) identifies NSC305787 as a selective destabilizer of the R495W mutant (ΔG = -8.612 kcal/mol) via steric hindrance to PIP2 recruitment, and THC as a WT stabilizer.

These findings highlight the PODXL-Ezrin complex as a "druggable" target for PODXL-altered cancers (e.g., pancreatic), potentially disrupting EMT and metastasis.

For the full manuscript, see TBC.

## Data Availability Notice

The image and structural data files associated with the molecular
dynamics simulation analysis (Figures S1–S9) are openly available on
Figshare.

These datasets include: - Image files generated from analysis -
Structural data derived from simulation workflows - Supplementary
materials referenced in the manuscript

They can be accessed and downloaded using the DOI below: DOI:
10.6084/m9.figshare.30604517 Link:
https://doi.org/10.6084/m9.figshare.30604517

Please refer to the Figshare entry for full details and file
descriptions.

Note: 
For further information regarding these datasets, please contact Stuart Lutimba at London South Bank University, who is responsible for maintaining and overseeing this data.
Inquiries can be made directly via:

Email: stuartlutimba@lsbu.ac.uk
Phone: +44 7442 453021
