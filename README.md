# VirtuousPocketome
Public repo of the VirtuousPocketome tool

This repository contains the simulation data for the paper "VirtuousPocketome: A Computational Tool for Virtual Screening of Protein Structures to Identify Similar Binding Sites".

The input data, required to reproduce the results in the paper, is organized in the following folders:

* SimulationData/

  * `MDP/`

    This folder contains the MD simulation parameters in GROMACS MDP format used for minimization, stepwise equilibration and production MD simulation.

  * `Topologies/`

    This folder contains the molecular topologies for the system (as obtained from CHARMM-GUI). Lipid-21 forcefield (Dickson et al., 2022) for lipids, AMBER19SB    (Tian et al., 2020) for the protein, ions and water, General Amber Force Field (GAFF2) forcefield (Wang et al., 2004) for Strychnine 

  * `SimulationInput/`

    This folder contains the input files (TPR format) for the equilibration and production MD simulations (after NVT+NPT equilibration).

---

# Acknowledgements:

The present work has been developed as part of the VIRTUOUS project, funded by the European Union’s Horizon 2020 research and innovation program under the Marie Sklodowska-Curie-RISE Grant Agreement No. 872181 (https://www.virtuoush2020.com/).

The authors would like to acknowledge Prof. M. Firdaus Raih from the Molecular Function Regulation Lab (http://mfrlab.org) for kindly providing us with the source code of ASSAM software. 

