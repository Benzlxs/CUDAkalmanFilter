# This package contains the implemenatation of Kalman Filter using a GPU.
Implemented the Kalman Filter Algorithms on GPU using CUDA programming language. Analysed the run-time performance gain obtained by parallel computation of the various stages of the algorithm


# Install
The GPU and CUDA [SDK](https://developer.nvidia.com/cuda-downloads) are required to run the demo code.

The GPU-based matrix inverse can be found [here](https://www.cs.waikato.ac.nz/~remco/)

# Start to run
```bash
$make
$./kalman -ns 1000 -no 250
```
```-ns``` is the number of state and ```-no``` is the number of observation for Kalman filter
