# CP-Variograms-CS-TropOce-Code
RAMS code and namelists for CS-TropOce simulations

Unzip rams_6.2.12.zip

Enter the rams_6.2.12 directory

There are two directories in the directory runs

HR_29_600_T12 contains namelists and run scripts for CS-TropOce-100m

SF16 contains namelists and run scripts for CS-TropOce-100m

In src/6.2.12/memory there are two versions of mem_tend.f90:
mem_tend.f90 and mem_tend.f90_sean_static_aero

Before running HR_29_600_T12, do not change the name of either file and recompile the model

Before running SF16, change the name of mem_tend.f90_sean_static_aero to mem_tend.f90 and recompile the model
