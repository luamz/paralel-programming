# Parallel Progamming using MPI and C

## Compiling
Type
``mpicc fileName.c -o fileName``

## Running
Type``mpirun -n X fileName`` where X is the number of processes you'd like
If your computer does not have enough slots available run ``mpirun -n X --oversubscribe fileName``
