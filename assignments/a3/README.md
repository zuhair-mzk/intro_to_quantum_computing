# Assignment 3: Quantum Algorithms

## Overview

This assignment explores fundamental quantum algorithms that demonstrate quantum computational advantage over classical approaches. Students learn to design, analyze, and understand the principles behind quantum speedup.

## Topics Covered

### 1. Deutsch-Jozsa Algorithm
- **Problem Statement**: Determining if a function is constant or balanced
- **Oracle Construction**: Black-box function implementation
- **Algorithm Design**: Single-query solution using superposition and interference
- **Quantum Advantage**: Exponential speedup over classical deterministic algorithms
- **Phase Kickback**: Understanding oracle-induced phase changes

### 2. Grover's Search Algorithm
- **Unstructured Search**: Finding a marked item in an unsorted database
- **Amplitude Amplification**: Increasing probability of correct answer
- **Grover Operator**: G = (2|ψ⟩⟨ψ| - I)(2|ω⟩⟨ω| - I)
- **Optimal Iterations**: √N queries for N items
- **Geometric Interpretation**: Rotation in 2D subspace
- **Oracle and Diffusion**: Two key components of the algorithm

### 3. Quantum Fourier Transform (QFT)
- **Classical DFT**: Discrete Fourier Transform review
- **QFT Circuit**: Efficient quantum implementation
- **Complexity**: O(n²) gates for n qubits vs O(n2ⁿ) classical
- **Applications**: Phase estimation, order finding, factoring
- **Inverse QFT**: Reversing the transformation

### 4. Shor's Algorithm (Introduction)
- **Integer Factorization**: Breaking RSA encryption
- **Period Finding**: Quantum subroutine for finding function periods
- **Modular Exponentiation**: Efficient quantum implementation
- **Classical Post-Processing**: Extracting factors from period
- **Complexity**: Polynomial time on quantum computer vs exponential classical
- **Cryptographic Implications**: Threat to current public-key systems

### 5. Quantum Algorithm Design Principles
- **Quantum Parallelism**: Superposition for simultaneous computation
- **Interference**: Constructive/destructive interference for answer extraction
- **Entanglement**: Correlation for complex problem solving
- **Measurement Strategy**: When and what to measure
- **Oracle Problems**: Black-box query complexity

## Key Concepts

- **Quantum Speedup**: Comparing quantum vs classical complexity
- **Query Complexity**: Number of oracle calls required
- **Superposition**: Exploiting parallel computation paths
- **Interference**: Amplifying correct answers, suppressing wrong ones
- **Phase Estimation**: Extracting eigenvalue information
- **Hadamard Transform**: Creating uniform superposition
- **Reversibility**: All operations except measurement are reversible

## Algorithm Comparison

| Algorithm | Problem | Classical Complexity | Quantum Complexity | Speedup |
|-----------|---------|---------------------|-------------------|---------|
| Deutsch-Jozsa | Constant vs Balanced | O(2^(n-1) + 1) worst case | O(1) | Exponential |
| Grover | Unstructured Search | O(N) | O(√N) | Quadratic |
| Shor | Integer Factorization | O(exp(n^(1/3))) | O(n³) | Exponential |
| QFT | Fourier Transform | O(n2ⁿ) | O(n²) | Exponential |

## Mathematical Tools

- Fourier analysis
- Eigenvalue decomposition
- Modular arithmetic
- Continued fractions (for Shor's algorithm)
- Probability amplitude calculations
- Unitary transformations

## Circuit Design

### Deutsch-Jozsa Circuit
```
|0⟩^⊗n ──H^⊗n── ┤Oracle├ ──H^⊗n── Measure
|1⟩    ──H────── ┤       ├
```

### Grover Iteration
```
|ψ⟩ ── ┤Oracle├ ── ┤Diffusion├ ── |ψ'⟩
```

### QFT Structure
- Hadamard gates
- Controlled phase rotations
- SWAP operations (bit reversal)

## Learning Objectives

By completing this assignment, students should be able to:
1. Implement and analyze the Deutsch-Jozsa algorithm
2. Design Grover's search algorithm for specific search problems
3. Construct quantum Fourier transform circuits
4. Understand the principles behind Shor's factoring algorithm
5. Compare quantum and classical algorithm complexities
6. Explain sources of quantum speedup
7. Design oracles for specific problem instances
8. Analyze the role of interference and superposition in quantum algorithms

## Practical Applications

- **Database Search**: Unstructured search optimization
- **Cryptanalysis**: Breaking classical encryption schemes
- **Optimization**: Quantum-enhanced search methods
- **Simulation**: Quantum system simulation using QFT
- **Machine Learning**: Quantum speedup for certain ML algorithms

## Files

**Note**: Assignment solutions have been removed to prevent academic dishonesty.

This README provides an overview of topics covered. For actual assignment problems, consult your course materials.

## ⚠️ Academic Integrity

**For current students**: Do not seek solutions from external sources. Complete assignments independently and consult with your instructor or TAs if you need help.

## Notes

This assignment represents the culmination of the course's quantum computing track, combining mathematical foundations (A1) and circuit design (A2) to implement powerful quantum algorithms that demonstrate genuine quantum advantage over classical computation.

---

**Course**: CSC D94 – Introduction to Quantum Computing & Quantum Information  
**Instructor**: Marcelo Ponce  
**University of Toronto, 2025**
