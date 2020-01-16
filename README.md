# uDGP
Repository of instances for the unassigned distance geometry problem (uDGP) created using a Julia language code and the procedure proposed by Lavor, 2006.

Lavor, Carlile. "On generating instances for the molecular distance geometry problem." Global optimization. Springer, Boston, MA, 2006. 405-414.

The instances are characterized by the number of the vertices in the structure. The repository contains instances from 5 up tp 500 vertices.

Each folder contains two subfolders, one for the instances, called "Instances". The second subfolder contains the 3D position of the vertices of each one of the previous instances -- this 3D positions are the raw data used to create the instances. 

The code used to create the instances and the solutions are available in the file "instance_generator.jl".

The parameters used for the instance generation are

-- number of vertices in each instance 

-- number of instance to be created

-- atoms distance

-- maximum distance between two atoms

-- consecutive atom angle (1.91)

-- torsional angle possibilities (1.0472 3.14159 5.23599 or 60, 180 and 300 degrees )


The instances are named as: "distance_frequency_sizeXX_instanceYY.dat", where XX is the number of vertices in the instance and YY is the numeration of instance. 

Instances are represented by the set of distances of each pair of the vertices in the problem. Since a distance may appears more than once, the data about how many times it appears (multiplicity) is presented in the instance. Each instance contains two columns, one for the multiplicity (left) and one for the value of the distance (right).
