# CP-Variograms-CS-TropOce-Code
RAMS code and namelists for CS-TropOce simulations

Unzip rams_6.2.12.zip

Enter the rams_6.2.12 directory

There are two directories in the directory runs

HR_29_600_T12 contains namelists and run scripts for CS-TropOce-100m

SF16 contains namelists and run scripts for CS-TropOce-1km

In src/6.2.12/memory there are two versions of mem_tend.f90:
mem_tend.f90_static_aero_off and mem_tend.f90_static_aero_on

Before running HR_29_600_T12, create a copy of mem_tend.f90_static_aero_off called mem_tend.f90 then recompile the model

Before running SF16, create a copy of mem_tend.f90_static_aero_on called mem_tend.f90 then recompile the model
