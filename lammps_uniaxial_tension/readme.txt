An example of a uniaxial tension simulation produces stress-strain data for calculating Young's modulus for armor. This folder contains 3 files: 
(1) TiAlV nanocomposites with 10 nanofillers D = 40 A >>>   Ti6Al4V_TiB_config1.data
(2) the lammps script to generate stress-strain file  >>>   lammps.in
(3) stress-strain file                                >>>   stress_strain data

Run lammps:  mpirun -np 10 lmp -in lammps.in | tee lammps.out
The result of running lammps is a file containing stress_strain data
