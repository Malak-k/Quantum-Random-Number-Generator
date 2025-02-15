# Quantum-Random-Number-Generator

This project utilizes quantum mechanics principles to generate truly random numbers. Unlike classical pseudo-random number generators (PRNGs), which rely on deterministic algorithms, this generator leverages quantum superposition and measurement to ensure genuine randomness.  

• How It Works  
- The algorithm uses quantum computing frameworks (such as Cirq) to create a quantum circuit.  
- A qubit is initialized in a (superposition state) using a Hadamard gate.  
- When measured, the qubit collapses probabilistically into **0 or 1**, ensuring true randomness.  
- By repeating this process, a sequence of quantum-generated random bits is produced.  

• Usage  
To run this project, install the required dependencies and execute the script. The output will be a stream of quantum-generated random numbers.  

• Requirements  
- Python 3+  
- Cirq, Qiskit or any quantum computing framework supporting quantum circuits  

• Future Improvements  
- Increase efficiency for large-scale random number generation  
- Explore cloud-based quantum computing for higher precision