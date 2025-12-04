# SVD-Rank-K-Approximation-
SVD Rank-K Approximation

This project implements Singular Value Decomposition (SVD) and Rank-K Matrix Approximation in C++. It began as part of my Introduction to Linear Algebra lab, but grew into a deeper exploration of how linear-algebra proofs connect to computational techniques.

Purpose of the Project

My goals with this project were:

To translate the theoretical concepts of SVD into a full C++ implementation.

To understand the differences between proof-based mathematics and computational linear algebra.

To practice designing code that operates on matrices of any size, including loading/saving matrix data for image compression.

To build a foundation I can later extend into parallel computing, GPU/CPU acceleration, and high-performance linear algebra.

This makes the project a stepping stone toward more advanced techniques such as:

Parallelized SVD and eigenvalue algorithms

CUDA or OpenCL acceleration

Multi-threaded numerical routines

GPU-accelerated image compression

HPC matrix operations using libraries like cuBLAS, cuSOLVER, Eigen, or OpenMP

What This Project Does

Loads a matrix (or image stored as a .txt file)

Computes its SVD components

Builds a rank-K approximation by selecting the top K singular values

Saves the compressed matrix

Allows experimentation with different ranks to compare quality vs. compression

Although the project currently uses CPU-only C++ code, the structure is designed so it can be extended with parallel or GPU-accelerated versions of:

Power Iteration

Deflation

Matrix multiplication

Eigenvalue computations

SVD refinement

Why SVD?

SVD is one of the most important algorithms in:

Image compression

Data reduction (PCA)

Machine learning

Signal processing

Numerical stability analysis

Implementing it manually builds strong intuition for:

Linear algebra

Matrix decompositions

Iterative numerical methods

Floating-point error behavior

Algorithmic efficiency

This makes it the perfect project for someone interested in mathematics, software engineering, and GPU/parallel computing.

Future Plans

As I learn more about GPU computing and high-performance C++/CUDA, I plan to add:

Parallel matrix multiplication (OpenMP)

CUDA kernels for power iteration

GPU-accelerated eigenvalue solver

Benchmarking CPU vs GPU performance

Real image compression using PPM/PNG loaders

How to Run

Compile the C++ files

Provide an input matrix file like catNew.txt

Run the program to generate:

U.txt

S.txt

V.txt

ApproxRankK.txt

Python scripts can be used to visualize the output or display reconstructed images.
