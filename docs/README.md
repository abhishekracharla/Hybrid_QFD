# Hybrid Quantum-Classical Burgers' Equation Solver

## Overview
The Hybrid Quantum-Classical Burgers' Equation Solver is a computational project that integrates quantum computing techniques with classical numerical methods to solve the Burgers' equation. This project aims to explore the potential of quantum algorithms in addressing complex fluid dynamics problems while providing a comparative analysis with classical approaches.

## Objectives
- Implement a hybrid solver that utilizes both quantum and classical methods to solve the Burgers' equation.
- Benchmark the performance of the quantum solver against classical solvers.
- Conduct scalability studies to evaluate the efficiency of the quantum algorithms as the problem size increases.
- Analyze the impact of noise in quantum computations and its effect on the results.

## Methodology
1. **Quantum Circuit Setup**: The project employs quantum circuits to represent the solution of the Burgers' equation. Variational quantum circuits are utilized to optimize the parameters for the quantum solution.
2. **Classical Solver**: A classical numerical method is implemented to serve as a reference solution for comparison with the quantum results.
3. **Benchmarking**: The performance of both solvers is evaluated in terms of execution time and accuracy, with results stored for further analysis.
4. **Scalability Studies**: The project investigates how the quantum solver scales with increasing grid sizes and qubit counts, providing insights into its practical applicability.
5. **Algorithm Comparison**: A detailed comparison of different algorithms used in the project is presented, highlighting their respective strengths and weaknesses.

## Usage Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd hybrid-burgers-qc-solver
   ```
3. Install the required dependencies (if applicable):
   ```
   pip install -r requirements.txt
   ```
4. Run the main implementation:
   - Open the Jupyter Notebook located in the `src` directory:
     ```
     jupyter notebook src/Hybrid_QTN_HSE_Main.ipynb
     ```
5. Review the output files and plots generated in the `output` and `plots` directories for results and visualizations.

## Output Files
- **Output Data**: Results of the simulations are stored in HDF5 and text files within the `output` directory.
- **Generated Plots**: Visual comparisons of the quantum and classical solutions, as well as scalability studies, are saved in the `plots` directory.

## Acknowledgments
This project leverages various libraries and frameworks for quantum computing and numerical simulations. Special thanks to the contributors and the open-source community for their invaluable resources and support.