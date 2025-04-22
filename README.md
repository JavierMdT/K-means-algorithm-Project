# K-means-algorithm-Project
This is a K-means algorithm using OpenMP and OpenMPI in C/C++. The goal is to make it as efficient as possible, parallelizing as much as possible. 

To compile: <br>
**mpicxx file_name.cpp -o file_name -fopenmp -O2**<br>
To run:<br>
**mpirun -np number_of_nodes file_name<br>**
