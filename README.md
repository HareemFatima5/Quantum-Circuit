# Quantum Circuit Simulation

This project demonstrates a basic **Quantum Circuit** implementation and simulation using Qiskit. 
It includes the construction of quantum gates, measurement of qubits, and simulation using Qiskit's `AerSimulator`.

## File Structure

- `Quantum_Circuit.ipynb` - Main Jupyter notebook demonstrating the creation and simulation of a quantum circuit.

## Project Overview

The notebook contains:
- Initialization of qubits.
- Application of Hadamard and other quantum gates.
- Measurement operations.
- Use of simulators (`AerSimulator`) to visualize circuit output.

## Requirements

Install the following packages before running:

```bash
!pip install qiskit qiskit-aer
```

## How to Run

1. Open the notebook in Jupyter Lab, VSCode, or Colab.
2. Run all cells step by step.

## Results

The final output represents the probability distribution of the measured quantum states (e.g., Measurement outcomes: {'0': 500, '1': 500}). 
This verifies the superposition or entanglement depending on your gate configuration.

## Accuracy

This is a simulation based project so accuracy here refers to:
- Fidelity of the simulated results matching theoretical quantum behavior.
- Correct interpretation of gate outputs.



