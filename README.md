FORTRAN code for calculating co-seismic static deformation based on the dislocation theory.

Highlights:

(1) incorporating with layered earth structure 

(2) incorporating with finite slip models 

(3) high numerical efficiency

For Windows user, the executable file is provided under folder "WindowsEXE". Linux user may compile the source codes with "gfortran" via a single command like, e.g.,

~>cd .../EDGRN/SourceCode

~>gfortran -o edgrn *.f -O3

to get the excutable code edgrn.

After start the executable code, the program ask for an input file in the ASCII format. An example input file is provided under folder "InputFile". You may change the input data included in this file for your own applications.

References

Wang, R., F. Lorenzo-Martín and F. Roth (2003), Computation of deformation induced by earthquakes in a multi-layered elastic crust - FORTRAN programs EDGRN/EDCMP, Computer and Geosciences, 29(2), 195-207.
