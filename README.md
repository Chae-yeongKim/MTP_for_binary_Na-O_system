# MTP for binary Na-O system 
We developed machine learning interatomic potentials using the MLIP package, which is a software developed by the group of A. Shappeev from Skoltech. 
The MLIP package is availble at DOI 10.1088/2632-2153/abc9fe. 

## Implemation of the 2B correction in LAMMPS package
Before implementing the MTP with 2B corrections, LAMMPS-MLIP interface developed by the group of A. Shappeev from Skoltech must be installed.
The detailed information on the MLIP package and interface can be found in DOI 10.1088/2632-2153/abc9fe or https://mlip.skoltech.ru/download/.

Each folder contians a potential model corresponding to the corrrctions for C= 0, 0.01, 0.02, 0.03 and 0.035, which are denoted by C_wo, C_001, C_002, C_003 and C_0035 in the paper.
 
1. Clone the potential file and 2B correction files 
2. Change the '/path/to/the/folder/of/MTP' in mlip.ini and rev_*.file according to your environment.
3. You can implement the MTP with 2B correction by using "include rev_*.file" in input file of LAMMPS.

