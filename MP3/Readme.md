## Lab3(MP3) Instruction

### Objective

The purpose of this lab is for you to practice with using the CUDA API by implementing a tiled Matrix Multiply kernel and its associated host code as shown in the lectures.

### Prerequisites

Before starting this lab, make sure that:

* You have completed all week 2 lectures or videos

* You have completed Lab2 (MP2)

### Instruction

You should edit the code in `template.cu` to perform the following:

* Allocate device memory

* Copy host memory to device

* Initialize thread block and kernel grid dimensions

* Invoke CUDA kernel

* Copy results from device to host

* Free device memory

* Write the CUDA kernel

Instructions about where to place each part of the code is
demarcated by the `//@@` comment lines.

If your solution is correct, you should be able to see the 
following output for each of the 10 test datasets:
```
--------------
Dataset  X
The dimensions of A are X x X
The dimensions of B are X x X
...
Solution is correct
```

