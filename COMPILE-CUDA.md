$ export PATH=/usr/local/cuda/bin:$PATH
$ export LD_LIBRARY_PATH=/usr/local/cuda/lib64:$LD_LIBRARY_PATH
$  nvcc Lattice_BoltzmannCuda.cu -lcublas
$ ./a.out