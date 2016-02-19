# lake-openmp
Parallelize the lake program using openmp

**Setup the PGI Compiler**

Append to your ~/.bashrc:

PGI=/usr/local/pgi; export PGI  
PATH=/usr/local/pgi/linux86-64/13.9/bin:$PATH  
LD_LIBRARY_PATH=/usr/local/pgi/linux86-64/13.9/libso:$LD_LIBRARY_PATH  
MANPATH=$MANPATH:$PGI/linux86/13.9/man  
LM_LICENSE_FILE=/usr/local/pgi/license.dat  
export LM_LICENSE_FILE PATH  
Now:  
For C++, use: pgCC -V x.c  
For ANSI C, use: pgcc -V x.c  
For debugging, use: pgdbg  
For OpenMP, add option: -mp  

