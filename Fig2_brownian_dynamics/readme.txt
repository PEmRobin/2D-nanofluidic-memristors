This folder contains codes for the Brownian simulation of a 2D slit using the LAMMPS software (https://lammps.sandia.gov/) under a time varying external field, to observe the memristor effect.

The lammps folder contains all customised LAMMPS fixes needed to implement the simulation:
fix_bd_2d implements 2D Brownian dynamics.
pair_buck implements the 2D+ interaction potential.
Copy these files to your local lamps/src folder and compile LAMMPS.
/!\ Doing so erase the buck pairwise potential. If you wish to keep it, simply rename the files for the 2D+ potential (eg: pair_2dp.h and pair_2dp.h)


The example folder contains the input LAMMPS code to simulate a 2D electrolyte under an time varying electric field:
input_bd : LAMMPS code
Efield.txt : applied electric field
Ip.txt : output file. Ionic current (cations only).
Im.txt : output file. Ionic current (anions only).