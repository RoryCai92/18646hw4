triangle.c is the original version of the function. Sequential using cpu
triangle_task.c is the task parallel version of the function.


To run the program with CPU (Sequential version):
make run_small
make run_medium
make run_larger

To run the pragram with task parallel version:
make run_small_gpu
make run_medium_gpu
make run_large_gpu

To change the number of threads used:
THREADS ?= number of threads (first line in makefile)