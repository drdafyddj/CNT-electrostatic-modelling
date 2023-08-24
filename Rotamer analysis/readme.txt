To perform molecular dynamics simulations of the BLIP-II AzF variants, open source software GROMACS was used (version 2021.5 in our models). 

Here, a modified CHARMM36 forcefield was used to account for the novel AzF residue. To use:
- Copy the relevant forcefield directory (charmm36_41_AzF.ff or charmm36_213_AzF.ff) into your working local directory.
- When executing 'pdb2gmx', select the forcefield in the local directory, rather than the top GROMACS forcefield options. 

Starting models (.pdb) are provided for BLIP-II 41 AzF and BLIP-II 213 AzF. All parameter files are provided (*.mdp).