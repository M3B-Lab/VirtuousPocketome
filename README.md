[![Virtuous button][Virtuous_image]][Virtuous link]

[Virtuous_image]: https://virtuoush2020.com/wp-content/uploads/2021/02/V_logo_h.png
[Virtuous link]: https://virtuoush2020.com/

Repository containing the files regarding the study: 

## VirtuousPocketome: A Computational Tool for Virtual Screening of Protein Structures to Identify Similar Binding Sites

Lorenzo Pallante<sup>1†</sup>, <i>Marco Cannariato<sup>1†</sup>, Lampros Androutsos<sup>2</sup>, Eric A. Zizzi <sup>1</sup>, Agorakis Bompotas<sup>3</sup>, Xhesika Hada<sup>1</sup>, Gianvito Grasso<sup>4</sup>, Athanasios Kalogeras<sup>3</sup>, Seferina Mavroudi<sup>2,5</sup>, Konstantinos Theofilatos<sup>2</sup> and Marco A. Deriu<sup>1*</sup>  </i>

<font size=2> <sup>1</sup>Polito<sup>BIO</sup>Med Lab, Department of Mechanical and Aerospace Engineering, Politecnico di Torino, 10129, Turin, Italy\
<sup>2</sup>InSyBio PC, Patras, 265 04, Greece 
<sup>3</sup>Industrial Systems Institute, Athena Research Center, 265 04 Patras, Greece.
<sup>4</sup> Dalle Molle Institute for Artificial Intelligence, Department of Innovative Technologies, Lugano-Viganello, 6962, Switzerland
<sup>5</sup> Department of Nursing, University of Patras, 265 04 Patras, Greece


† Lorenzo Pallante and Marco Cannariato contributed equally to this study.

</font>

The preprint of the article can be accessed at this [link]

--------

### Repo Structure

The input data, required to reproduce the results in the paper, is organized in the following folders:

* SimulationData/

  * `MDP/`

    This folder contains the MD simulation parameters in GROMACS MDP format used for minimization, stepwise equilibration and production MD simulation.

  * `Topologies/`

    This folder contains the molecular topologies for the system (as obtained from CHARMM-GUI). Lipid-21 forcefield (Dickson et al., 2022) for lipids, AMBER19SB    (Tian et al., 2020) for the protein, ions and water, General Amber Force Field (GAFF2) forcefield (Wang et al., 2004) for Strychnine 

  * `SimulationInput/`

    This folder contains the input files (TPR format) for the equilibration and production MD simulations (after NVT+NPT equilibration).

---

### Acknowledgements:

The present work has been developed as part of the VIRTUOUS project, funded by the European Union’s Horizon 2020 research and innovation program under the Marie Sklodowska-Curie-RISE Grant Agreement No. 872181 (https://www.virtuoush2020.com/).

The authors would like to acknowledge Prof. M. Firdaus Raih from the Molecular Function Regulation Lab (http://mfrlab.org) for kindly providing us with the source code of ASSAM software. 

