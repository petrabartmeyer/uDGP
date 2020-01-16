# uDGP
Repository of instances for the unassigned distance geometry problem (uDGP) created using a JUlia language code and the procedure proposed by Lavor, 2006.

Lavor, Carlile. "On generating instances for the molecular distance geometry problem." Global optimization. Springer, Boston, MA, 2006. 405-414.

The instances are characterized by the number of the vertices in the structure. The repository contains instances from 5 up tp 500 vertices.

Each folder contains two subfolders, one for the instances, called "Instances". The second subfolder contains the 3D position of the vertices of each one of the previous instances -- this 3D positions are the raw data used to create the instances. 

The code used to create the instances and the solutions are available in the file "instance_generator.jl".
