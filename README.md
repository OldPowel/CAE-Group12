# CAE-Group12
Tasks to be done before starting the individual tasks

1. Model the geometry as shown in Fig. 1 using Ansys. To account for the stray fields add
additional air of 5 µm at bottom, top and right side of the capacitor. Put all commands
needed for the modeling as well as the meshing process into a plain text file Meshscript.in
(= your script file) and make sure that the dimensions and the used mesh size dx are easily
changable (i.e. define them as parameter at the beginning of your script and use only these
parameter for the modeling commands). Create in total seven mesh files for the given geometry,
using the following mesh sizes dx as the only variable parameter
   dx = 1:5mm, 1:25mm, 1mm, 0:75mm, 0:5mm, 0:25mm, 0:125mm .
   
2. Derive an analytic formula to estimate the capacitance of the assembly shown in Fig. 1. You
can assume that electrode 1 and electrode 2 form a plate capacitor of radius r1 and electrode
2 and electrode 3 another plate capacitor of radius r2. How do you have to connect these two
capacitors and what is the resulting formula for the overall capacitance of the setup depending
on r1 and r2?
