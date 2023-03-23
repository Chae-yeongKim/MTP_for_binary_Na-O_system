# MTP for binary Na-O system 

We developed the machine learning interatomic potnetials using MLIP pacakge (a software developed by the group of A. Shappeev from Skoltech) The MLIP package is availble at DOI 10.1088/2632-2153/abc9fe. 


# Implemation in LAMMPS package
Before implementing the MTPs and 2B correction, LAMMPS-MLIP interface developed by the group of A. Shappeev from Skoltech must be installed.
The detailed information on that can be found in DOI 10.1088/2632-2153/abc9fe or  https://mlip.skoltech.ru/download/.
 
1. Clone the MTPs and 2B correction files 
2. Change the '/path/to/the/folder/of/MTP' in mlip.ini and rev_*.file according to your environment.
3. By using the command "include rev_*.file" in input file of LAMMPS, you can use our developed MTP with 2B correction.

