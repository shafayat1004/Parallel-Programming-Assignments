

## Lab1(MP1) Instructions

### Objective

The purpose of this lab is for you to become familiar with using the CUDA API by implementing a simple vector addition kernel 
and its associated host code as shown in the lectures.

### Prerequisites

Before starting this lab, make sure that:

* You have completed all week 1 lectures or videos

* You have completed Lab0 (MP0)

* Chapter 2 of the text book would also be helpful

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

If your solution is correct, you should be able to see the following
output for each of the 10 test datasets:
```
--------------
Dataset  X
The input length is XX
Solution is correct
```


