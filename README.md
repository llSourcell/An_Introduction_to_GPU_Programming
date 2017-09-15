# An_Introduction_to_GPU_Programming
This is the code for "An introduction to GPU Programming with CUDA" by Siraj Raval on Youtube

# Coding Challenge - Due Date Thursday, September 21, 2017 

This weeks challenge is to create a simple C++ program that you can parallelize using CUDA. Document it's speed before and after using CUDA to demonstrate that you were able to optimize your code via the GPU. [Here](https://www.cs.cmu.edu/~scandal/nesl/algorithms.html) are some examples of algorithms you can parallelize. Bonus points if you parallelize a simple neural network. Good luck!

## Overview

This is the code for [this](https://youtu.be/1cHx1baKqq0) video on Youtube by Siraj Raval. This is an introduction to parallel programming on the GPU by using Nvidia's CUDA toolkit. We're going to add two arrays together, and parallelize that process using CUDA (an extension of C). 

## Dependencies

* CUDA (https://developer.nvidia.com/cuda-downloads) 

## Usage

Run the following command to compile

`nvcc add.cu -o add_cuda`

This command to execute

`./add_cuda`

And this command to profile (clock) it

`nvprof ./add_cuda`

## Credits

The credits for this code go to Nvidia. I've merely created a wrapper to get people started.

