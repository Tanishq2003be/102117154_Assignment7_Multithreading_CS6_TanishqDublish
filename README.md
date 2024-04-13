# Multithreading-matrix-multiplication

## Overview

This Python script benchmarks the performance of matrix multiplication using multi-threading. It generates 100 random matrices of size 1000x1000 and multiplies each of them with a constant matrix of the same size. The performance is measured for different numbers of threads ranging from 1 to 8.

## Prerequisites

1. Python 3.x
2. NumPy
3. Matplotlib
4. Pandas

The script will generate the following outputs: - Table showing the time taken for matrix multiplication with different numbers of threads. - Graph plotting the matrix multiplication time versus the number of threads. - CPU usages (if available). - Graph of CPU usage with percentage 0 to 100 percent

## Results Interpretation

1. **Time Taken**: Refers to the duration it takes to perform a specific operation or task. In this context, it represents the time taken to perform matrix multiplication.

2. **CPU Usage**: Represents the percentage of CPU (Central Processing Unit) capacity utilized by the system at a given moment. It indicates how much of the CPU's processing power is being used.

3. **Number of Threads**: Refers to the number of concurrent execution units within a process. In this code, it indicates the number of threads used for performing matrix multiplication in parallel. Increasing the number of threads can potentially improve performance by utilizing multiple CPU cores concurrently.

## Resultant Table

![Result table](./Result%20table.png)

## CPU usage Graph

![Cpu usage](./Cpu%20usage.png)

## Time VS Threads

![Threads VS Time](./Time%20vs%20Threads.png)
