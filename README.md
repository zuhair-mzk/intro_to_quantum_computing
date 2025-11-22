# CSC D94 – Introduction to Quantum Computing & Quantum Information

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![Quantum Computing](https://img.shields.io/badge/Quantum-Computing-blueviolet?style=for-the-badge)

**Instructor:** Marcelo Ponce  
**Institution:** University of Toronto  
**Year:** 2025

---

## 📚 Course Description

This course provides a comprehensive introduction to the principles and applications of quantum computing and quantum information theory. Students explore the mathematical foundations of quantum mechanics, quantum algorithms, quantum hardware, and emerging topics in post-quantum cryptography.

The course bridges theoretical physics, computer science, and information theory, offering hands-on experience with quantum computing platforms and contemporary research challenges.

---

## 🎯 Topics Covered

### Mathematical Foundations
- **Linear Algebra**: Vector spaces, tensor products, eigenvalues and eigenvectors
- **Differential Equations**: ODEs and PDEs in quantum contexts
- **Probability & Statistics**: Quantum measurement and statistical mechanics
- **Brownian Motion**: Stochastic processes in quantum systems

### Physics Background
- **Modern Physics**: Double-slit experiment, wave-particle duality
- **Quantum Mechanics Basics**: Postulates, Schrödinger equation, measurement problem

### Quantum Computing Core
- **Qubits & Quantum States**: Superposition, entanglement, Bloch sphere representation
- **Quantum Gates**: Single-qubit and multi-qubit operations
- **Quantum Circuits**: Design and analysis
- **Quantum Algorithms**: Deutsch-Jozsa, Grover's search, Shor's factoring algorithm
- **Quantum Measurement**: Projective measurements, POVM

### Advanced Topics
- **Quantum Tunneling**: Applications in quantum computing
- **Bell Inequalities**: Quantum non-locality and entanglement verification
- **Quantum Hardware**: Superconducting qubits, ion traps, photonic systems
- **Post-Quantum Cryptography**: Lattice-based methods, quantum-resistant algorithms
- **Quantum Key Distribution (QKD)**: BB84, E91 protocols

### Practical Experience
- **Xanadu Codebook Workshop**: Hands-on quantum programming with PennyLane

---

## 📋 Course Timeline

| Week | Topic | Description |
|------|-------|-------------|
| 1-2 | Mathematical Foundations | Linear algebra review, vector spaces, tensor products |
| 3 | Probability & Modern Physics | Statistical foundations, double-slit experiment |
| 4-5 | Quantum Mechanics Basics | Postulates, qubits, quantum states |
| 6-7 | Quantum Computing Intro | Quantum gates, circuits, measurement |
| 8-9 | Quantum Algorithms | Deutsch-Jozsa, Grover, Shor's algorithm |
| 10 | QC Workshop | Xanadu Codebook hands-on session |
| 11 | Quantum Tunneling | Physical phenomena and applications |
| 12 | Bell Inequalities | Non-locality and entanglement tests |
| 13 | Quantum Hardware | Physical implementations, error rates |
| 14 | Post-Quantum Cryptography | PQC families, lattice methods, QKD |

---

## 📝 Assignments

### [Assignment 1: Quantum Mechanics Foundations](./assignments/a1/)
**Topics**: Linear algebra, quantum states, measurement, density matrices  
**Key Concepts**: Tensor products, eigenvalue problems, quantum measurement postulates

### [Assignment 2: Quantum Gates & Circuits](./assignments/a2/)
**Topics**: Single and multi-qubit gates, quantum circuits, entanglement  
**Key Concepts**: Hadamard, CNOT, phase gates, Bell states, circuit design

### [Assignment 3: Quantum Algorithms](./assignments/a3/)
**Topics**: Deutsch-Jozsa, Grover's algorithm, quantum Fourier transform  
**Key Concepts**: Oracle construction, amplitude amplification, quantum speedup

---

## 🎤 Presentation Summary

### [Post-Quantum Cryptography, Lattice Methods & Quantum Key Distribution](./presentation/)

**Overview**: This presentation explores the intersection of quantum computing threats and cryptographic defenses, covering both post-quantum cryptography (PQC) and quantum key distribution (QKD).

**Key Sections**:
- **Motivation**: The quantum threat to classical cryptography
- **Shor's Algorithm**: Breaking RSA and elliptic curve cryptography
- **PQC Families**: Lattice-based, code-based, hash-based, multivariate polynomial methods
- **Lattice Methods**: Learning With Errors (LWE) and Ring-LWE foundations
- **NIST Standards**: Kyber (encryption), Dilithium (signatures)
- **NTRU**: Alternative lattice-based approach
- **Quantum Key Distribution**: BB84 and E91 protocols
- **PQC vs QKD**: Comparative analysis of approaches

**📦 Complete Materials**: [View presentation slides, iPad notes, and recording](https://drive.google.com/drive/folders/179TPIacUaYcYeV8Jj4zznRIGlUpDnQD3)

Full details available in the [presentation folder](./presentation/).

---

## 📚 References

### Textbooks
- Nielsen, M. A., & Chuang, I. L. (2010). *Quantum Computation and Quantum Information*. Cambridge University Press.
- Mermin, N. D. (2007). *Quantum Computer Science: An Introduction*. Cambridge University Press.
- Kaye, P., Laflamme, R., & Mosca, M. (2007). *An Introduction to Quantum Computing*. Oxford University Press.

### Post-Quantum Cryptography
- Bernstein, D. J., & Lange, T. (2017). *Post-quantum cryptography*. Nature, 549(7671), 188-194.
- NIST Post-Quantum Cryptography Standardization Project: https://csrc.nist.gov/projects/post-quantum-cryptography

### Quantum Key Distribution
- Ekert, A. K. (1991). *Quantum cryptography based on Bell's theorem*. Physical Review Letters, 67(6), 661.
- Bennett, C. H., & Brassard, G. (2014). *Quantum cryptography: Public key distribution and coin tossing*. Theoretical Computer Science, 560, 7-11.

### Online Resources
- Xanadu Codebook: https://codebook.xanadu.ai/
- Qiskit Textbook: https://qiskit.org/textbook/
- IBM Quantum Experience: https://quantum-computing.ibm.com/

---

## 🔗 Course Resources

- **Course Website**: [Insert course website URL]
- **Google Drive**: [Course Materials & Presentations](https://drive.google.com/drive/folders/179TPIacUaYcYeV8Jj4zznRIGlUpDnQD3)
- **Lecture Notes**: Available in the [`/notes`](./notes/) folder
- **Additional Resources**: Check the [`/resources`](./resources/) folder

---

## 📂 Repository Structure

```
d94/
├── README.md                          # This file
├── LICENSE                            # MIT License
├── .gitignore                        # Python, LaTeX, Jupyter ignores
├── assignments/
│   ├── a1/                           # Assignment 1
│   ├── a2/                           # Assignment 2
│   └── a3/                           # Assignment 3
├── presentation/                      # PQC & QKD presentation
├── notes/                            # Lecture notes and study materials
└── resources/                        # Additional resources and references
```

---

## 🛠️ Tools & Technologies

- **Programming**: Python, NumPy, Matplotlib
- **Quantum Frameworks**: Qiskit, PennyLane, Cirq
- **Documentation**: LaTeX, Markdown, Jupyter Notebooks
- **Version Control**: Git, GitHub

---

## 📄 License

This repository is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

## 👤 Author

**Zuhair**  
University of Toronto, 2025

---

## ⚠️ Academic Integrity & Copyright Notice

**IMPORTANT**: This repository is for educational and portfolio purposes only.

### Copyright
- All original work, solutions, and materials in this repository are **© 2025 Zuhair**
- This work is protected under copyright law and the MIT License (for code/documentation structure only)

### Academic Integrity
- **DO NOT** copy, reproduce, or submit any part of this work as your own
- **DO NOT** distribute assignment solutions or answers
- Plagiarism is a serious academic offense with severe consequences
- Use this repository as a reference for structure and learning approaches only

### For Students
If you are currently taking CSC D94 or a similar course:
- Work through problems independently
- Consult your instructor and TAs for help
- Academic dishonesty will result in failure and disciplinary action
- Learn the concepts rather than copying solutions

**Violating academic integrity policies may result in:**
- Automatic failure of the course
- Academic misconduct on your transcript
- Suspension or expulsion from the university
- Long-term damage to your academic and professional reputation

---

## 🙏 Acknowledgments

Special thanks to Professor Marcelo Ponce for an inspiring course in quantum computing and quantum information theory.
