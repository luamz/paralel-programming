# Parallel Progamming

## MPI
### Compiling
Type
``mpicc fileName.c -o fileName``

### Running
Type``mpirun -n X fileName`` where X is the number of processes you'd like

If your computer does not have enough slots available run ``mpirun -n X --oversubscribe fileName``

## OpenMP

Number of threads can be set up externally by using the following enviroment variable:
``export OMP_NUM_THREADS=2`` (bash)

### Compiling
Type
``gcc fileName.c -o fileName -fopenmp``

### Running
Type``./hello_world`` 

