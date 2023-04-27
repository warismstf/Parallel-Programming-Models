Comparative Study of OpenMPI and Other Parallel Programming Models

This repository contains the codes used in the project on a comparative study of OpenMPI and other parallel programming models on many-core and multi-core architectures. The project includes the implementation and performance evaluation of parallel matrix multiplication, parallel sorting, and parallel Monte Carlo simulations using OpenMP, MPI, OpenACC, and a hybrid of MPI and OpenACC. The project also involves comparing the performance of these parallel programming models on various many-core and multi-core architectures.

Matrix Multiplication
The openmp_matrix_multiplication.cpp file contains the code for parallel matrix multiplication using OpenMP. The mpi_openacc_matrix_multiplication.cpp file contains the code for parallel matrix multiplication using a hybrid of MPI and OpenACC.

Sorting
The openmp_parallel_sort.cpp file contains the code for parallel sorting using OpenMP. The mpi_openacc_parallel_sort.cpp file contains the code for parallel sorting using a hybrid of MPI and OpenACC.

Monte Carlo Simulations
The openmp_monte_carlo.cpp file contains the code for parallel Monte Carlo simulations using OpenMP. The mpi_openacc_monte_carlo.cpp file contains the code for parallel Monte Carlo simulations using a hybrid of MPI and OpenACC.

Dependencies
OpenMP
MPI
OpenACC
Usage
To compile the codes, you can use a C++ compiler such as g++ with the appropriate flags to link the OpenMP, MPI, and OpenACC libraries. For example, to compile the OpenMP matrix multiplication code, you can use the following command:

Copy code
g++ -fopenmp openmp_matrix_multiplication.cpp -o openmp_matrix_multiplication
To run the compiled code, you can use the following command:

bash
Copy code
./openmp_matrix_multiplication
License
This project is licensed under the MIT License.
