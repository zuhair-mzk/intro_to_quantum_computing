# Assignment 2: Quantum Gates & Circuits

## Overview

This assignment explores the fundamental building blocks of quantum computation: quantum gates and quantum circuits. Students learn to design, analyze, and manipulate quantum circuits to perform computational tasks.

## Topics Covered

### 1. Single-Qubit Gates
- **Pauli Gates**: X, Y, Z operations (quantum NOT, phase flips)
- **Hadamard Gate**: Creating superposition states
- **Phase Gates**: S, T, and general rotation gates (R_φ, R_θ)
- **Universal Gate Sets**: Decomposition of arbitrary single-qubit unitaries

### 2. Multi-Qubit Gates
- **CNOT Gate**: Controlled-NOT and entanglement generation
- **Controlled Gates**: General controlled-U operations
- **SWAP Gate**: Exchanging quantum states
- **Toffoli Gate**: Three-qubit controlled-controlled-NOT
- **Fredkin Gate**: Controlled-SWAP operation

### 3. Quantum Circuits
- **Circuit Composition**: Sequential and parallel gate operations
- **Circuit Diagrams**: Standard notation and conventions
- **Unitary Evolution**: Computing circuit output states
- **Circuit Depth**: Complexity measures and optimization
- **Reversibility**: All quantum operations are unitary and reversible

### 4. Entanglement
- **Bell States**: Maximally entangled two-qubit states (|Φ⁺⟩, |Φ⁻⟩, |Ψ⁺⟩, |Ψ⁻⟩)
- **Bell Circuit**: Creating entanglement with H and CNOT
- **EPR Pairs**: Einstein-Podolsky-Rosen correlations
- **GHZ States**: Multi-qubit entanglement
- **Quantum Teleportation**: Circuit design and protocol

### 5. Quantum Circuit Design
- **Gate Decomposition**: Breaking complex operations into elementary gates
- **Circuit Equivalence**: Identifying equivalent circuits
- **Optimization**: Reducing gate count and circuit depth
- **No-Cloning Theorem**: Fundamental limitations of quantum copying

## Key Concepts

- **Unitarity**: All quantum gates are unitary matrices (U†U = I)
- **Reversibility**: Quantum computation is inherently reversible
- **Basis States**: Computing in computational, Hadamard, and other bases
- **Matrix Representations**: Working with gate matrices and tensor products
- **Controlled Operations**: Conditioning quantum gates on control qubits

## Circuit Examples

### Bell State Creation
```
|00⟩ ──H── ●── |Φ⁺⟩ = (|00⟩ + |11⟩)/√2
        │
        X
```

### Quantum Teleportation
- Entanglement preparation
- Bell measurement
- Classical communication
- Conditional corrections

## Mathematical Tools

- Unitary matrix operations
- Tensor products of gates
- Matrix multiplication for circuit evaluation
- Change of basis transformations
- Entanglement entropy calculations

## Learning Objectives

By completing this assignment, students should be able to:
1. Apply single and multi-qubit gates to quantum states
2. Design quantum circuits for specific computational tasks
3. Compute circuit outputs using matrix multiplication
4. Create and manipulate entangled states
5. Decompose complex operations into elementary gates
6. Analyze circuit complexity and depth
7. Understand the role of entanglement in quantum computing

## Files

- `qc_a2.pdf` - Assignment questions and problems
- `A2_D94.pdf` - Additional assignment materials

## Notes

This assignment builds on Assignment 1's foundations and prepares students for quantum algorithms covered in Assignment 3. Understanding quantum gates and circuits is essential for implementing any quantum algorithm.

---

**Course**: CSC D94 – Introduction to Quantum Computing & Quantum Information  
**Instructor**: Marcelo Ponce  
**University of Toronto, 2025**
