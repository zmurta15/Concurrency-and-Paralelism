# Concurrency and Parallelism 2021-22

### Agent-based Simulation of Fire Extinguishing

EduHPC 2019: Peachy assignment

(c) 2019 Arturo Gonzalez-Escribano, Jorge Fernandez-Fabeiro
Group Trasgo, Universidad de Valladolid (Spain)

--------------------------------------------------------------

    Group Id: G16
    Member 1: João Vargues (55185)
    Member 2: José Murta (55226)
    Member 3: Diogo Rodrigues (56153)

--------------------------------------------------------------

How to compile this program:

On directory Code execute one of the next options in the terminal to compile the program:
1. make all 
2. for sequential version -> gcc -O3  extinguishing.c -lm -o extinguishing_seq  
and for paralell version -> gcc -O3  -fopenmp extinguishing_omp.c -lm -o extinguishing_omp 

How to run the examples:

On directory code execute one of the next options in the terminal to run the example:
1. ./executable -f test_files/test_file_name
2. ./executable rows columns maxIter numTeams [ teamX teamY teamType ... ] numFocalPoints [ focalX focalY focalStart focalTemperature ... ]

