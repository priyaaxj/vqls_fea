# QAOA - Quantum Approximate Optimization Algorithm

Welcome to the QAOA project! This project demonstrates how to use the Quantum Approximate Optimization Algorithm to solve combinatorial optimization problems, such as the Max-Cut problem, using Qiskit.

## 🚀 Overview

QAOA is a hybrid quantum-classical algorithm designed for NISQ (Noisy Intermediate-Scale Quantum) devices. It combines quantum circuits for solution preparation and classical optimization for parameter tuning.

In this project, we:
- Define a cost function based on a graph.
- Construct the QAOA ansatz.
- Run the algorithm using Qiskit.
- Analyze the results and probability distribution.

## 🧠 Key Concepts

- Qiskit: IBM's open-source quantum computing SDK.
- QAOA: Algorithm for solving optimization problems using parameterized quantum circuits.
- Hybrid Optimization: Uses a classical optimizer (like COBYLA or SPSA) to minimize the cost function.
- Quantum Circuit: Built using the cost and mixer Hamiltonians.

## 🔧 Installation

Make sure you have Python 3.8+ installed
