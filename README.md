# parmetis4py

Python bindings for the ParMETIS graph partitioning library.

## Installation instructions

We need to find METIS, ParMETIS and MPI. If you are on Ubuntu 18.04 and have obtained METIS and ParMETIS via PETSc, then just set the following environment variables

    export PETSC_DIR=/path/to/your/petsc/
    export PETSC_ARCH=
    export MPICC=mpicc
    export CC=mpicc
    export CXX=mpic++

Then just run
    
    pip install -e .

and things should work.
