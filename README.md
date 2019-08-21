# Awesome CUDA
Some CUDA tutorial and materials.

## Tutorials
* http://blog.csdn.net/column/details/hpc-gpu.html
* http://supercomputingblog.com/cuda-tutorials/
* https://zhuanlan.zhihu.com/c_116100152
* https://jhui.github.io/2017/03/06/CUDA/

## Examples
### Convolution
* https://www.evl.uic.edu/sjames/cs525/final.html

## CUDA Thread Indexing Cheatsheet
* https://cs.calvin.edu/courses/cs/374/CUDA/CUDA-Thread-Indexing-Cheatsheet.pdf

## Trivia
### ```cudaMallocManaged()```
* cudaMallocManaged() with initialize data on GPU can reduce a great amount of memory transferring time from CPU to GPU.
* cudaMallocManaged() + cudaMemPrefetchAsync() can also reduce a great amount of memory transferring time **both CPU to GPU** or **GPU to CPU**.
    * the reason is that cudaMemPrefetchAsync() can prevent page fault.
### ```volatile```
* https://baiweiblog.wordpress.com/category/gpu/
