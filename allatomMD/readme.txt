This folder contains codes for the all-atom simulation of a 2D slit using the LAMMPS software (https://lammps.sandia.gov/).

The code allows to change the type of salt (NaCl, CaSO4...), the confining material (hBN, graphene) and the water model (SPCE, TIP4P...). 

To illustrate this fact, two examples are included:

- CaSO4 in a graphene slit and TIP4P water,
- NaCl in a hBN slit and SPCE water.

Each folder contains 2 files:

- input : LAMMPS code,
- ini_config.data : initial configuration.
when the simulation is finished, the output takes the form of a dump.atom file which can be visualized using VMD (https://www.ks.uiuc.edu/Research/vmd/)