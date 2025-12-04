# SVD-Rank-K-Approximation-
SVD Rank-K Approximation (C++)

This project implements Singular Value Decomposition and Rank-K Matrix Approximation fully in C++. I built it as part of my linear algebra coursework to bridge the gap between mathematical theory and practical numerical computation, with the long-term goal of extending it into parallel computing, GPU acceleration, and high-performance linear algebra.

Features

Load matrices or images stored as .txt

Compute SVD components (U, Σ, Vᵀ)

Build rank-K approximations using top singular values

Save compressed/approximated matrices

Code designed to scale to matrices of any size

Motivation

I’m interested in GPU/CPU software, parallel algorithms, and HPC. Implementing SVD from scratch helps build intuition for numerical stability, iterative algorithms, and matrix decompositions—skills that carry into GPU computing (CUDA), OpenMP, cuBLAS/cuSOLVER, and scientific programming.

How to Run

Compile the C++ files

Provide an input matrix (e.g., catNew.txt)

Run the program to generate:

U.txt

S.txt

V.txt

ApproxRankK.txt

<details> <summary><strong>Why SVD?</strong></summary>

SVD is fundamental in image compression, PCA, machine learning, signal processing, and numerical stability.
Implementing it manually builds strong intuition for:

Matrix decompositions

Iterative eigenvalue methods

Floating-point error behavior

Algorithmic efficiency

</details>
<details> <summary><strong>Future Extensions (GPU, HPC, Parallel)</strong></summary>

Parallel matrix multiplication (OpenMP)

CUDA kernels for power iteration

GPU-accelerated eigenvalue solver

CPU vs GPU performance benchmarking

Real image compression using PPM/PNG loaders

</details>
