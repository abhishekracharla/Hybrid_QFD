# Hybrid Quantum-Classical Burgers' Equation Solver
## WOMANIUM & WISER 2025 Quantum Projects


## Overview
The Hybrid Quantum-Classical Burgers' Equation Solver is a computational project that leverages both quantum and classical computing techniques to solve the Burgers' equation, a fundamental partial differential equation in fluid dynamics. This project aims to explore the potential of quantum computing in simulating complex physical systems and to compare its performance against classical methods.

## Objectives
- Implement a hybrid solver that combines quantum and classical approaches to solve the Burgers' equation.
- Benchmark the performance of the quantum solver against classical methods.
- Analyze the scalability of the quantum approach with varying grid sizes and qubit configurations.
- Compare different algorithms used in the project to identify their strengths and weaknesses.

## Methodology
The project consists of the following key components:
1. **Quantum Circuit Setup**: Define the variational quantum circuit used for solving the Burgers' equation.
2. **Classical Solver**: Implement a classical reference solver for comparison.
3. **Benchmarking**: Run simulations to compare the performance of the quantum and classical solvers.
4. **Scalability Studies**: Investigate how the performance of the quantum solver scales with increasing grid sizes and qubit counts.
5. **Algorithm Comparison**: Evaluate different algorithms used in the project to understand their trade-offs.

## Usage Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   cd hybrid-burgers-qc-solver
   ```
2. Install the required dependencies. Ensure you have Python and the necessary libraries installed:
   ```
   pip install -r requirements.txt
   ```
3. Run the main implementation:
   ```
   jupyter notebook src/Hybrid_QTN_HSE_Main.ipynb
   ```
4. Review the output files in the `output` directory for results and analysis.

## Output Files
- **Output Data**: Results of the simulations are stored in the `output` directory, including:
  - `burgers_results.h5`: Results of the quantum solver.
  - `burgers_noisy_results.h5`: Results with noise included.
  - `hardware_results.h5`: Results from quantum hardware execution.
  - `resource_analysis.txt`: Analysis of resources used.
  - `scalability_results.csv`: Performance metrics for scalability studies.
  - `algorithm_comparison.md`: Comparison of different algorithms.

- **Plots**: Visualizations of the results are saved in the `plots` directory, including:
  - `quantum_vs_classical.png`: Comparison of quantum and classical solutions.
  - `noisy_quantum_vs_classical.png`: Comparison of noisy quantum and classical solutions.
  - `hardware_comparison.png`: Visualization of hardware execution results.
  - `scalability_plot.png`: Plot of scalability study results.

## Acknowledgments
This project utilizes various libraries and frameworks for quantum computing and numerical simulations. Special thanks to the contributors and the open-source community for their valuable resources and support.