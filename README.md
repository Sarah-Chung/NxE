# Neutral-with-Epistasis (NxE)
Neutral-with-Epistasis protein sequence evolutionary model in MATLAB.

**Any publications resulting from the use of NxE should cite:**

Schmelkin L, Carnevale V, Haldane A, Townsend JP, Chung S, Levy RM, Kumar S. 2025. Epistasis plays a limited role in driving entrenchment during neutral protein evolution. bioRxivorg [Internet]:2025.01.09.632266. Available from: https://www.biorxiv.org/content/10.1101/2025.01.09.632266v1

---
# Overview
This repository contains the relevant information for modifying the original Sequence Evolution with Epistatic Contributions (SEEC) model described in [de la Paz et al. 2020](https://www.pnas.org/doi/10.1073/pnas.1913071117) for NxE sequence evolution. Code for the SEEC model can be accessed here: [https://github.com/AlbertodelaPaz/SEEC](https://github.com/AlbertodelaPaz/SEEC)

# Technologies
- MATLAB_R2024a
    - Bioinformatics Toolbox
    - Statistics and Machine Learning Toolbox

# Files
- `NxE.diff`: Diff file describing the modifications made to the original SEEC codebase.

# Usage
Changes outlined in `NxE.diff` should be applied to the `Probevolution.m` script in the original SEEC model, which can be downloaded from the SEEC repository ([https://github.com/AlbertodelaPaz/SEEC](https://github.com/AlbertodelaPaz/SEEC)).

Accompanying ortho-domain alignments can be downloaded from the NxE Dryad repository [10.5061/dryad.g1jwstr70](10.5061/dryad.g1jwstr70).

Potts Hamiltonian parameters for evolved domains can be downloaded from the original SEEC Dryad repository [https://doi.org/10.5061/dryad.2ngf1vhj8](https://doi.org/10.5061/dryad.2ngf1vhj8).

# References

### SEEC paper
de la Paz, J. A., Nartey, C. M., Yuvaraj, M., & Morcos, F. Epistatic contributions promote the unification of incompatible models of neutral molecular evolution. Proceedings of the National Academy of Sciences. https://doi.org/10.1073/pnas.1913071117 (2020)

### SEEC repository
de la Paz, J. A., Nartey, C. M., Yuvaraj, M., & Morcos, F. Epistatic contributions promote the unification of incompatible models of neutral molecular evolution. GitHub. https://github.com/AlbertodelaPaz/SEEC (2020).

### Potts Hamiltonian parameters
de la Paz, J. A., Nartey, C. M., Yuvaraj, M., & Morcos, F. Epistatic contributions promote the unification of incompatible models of neutral molecular evolution. Dryad. [doi: 10.5061/dryad.2ngf1vhj8](10.5061/dryad.2ngf1vhj8) (2020).