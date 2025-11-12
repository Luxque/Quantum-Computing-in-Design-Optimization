# Quantum Computing in Design Optimization

Repository of demonstration materials developed for the undergraduate research project at Rensselaer Polytechnic Institute (RPI): "Quantum Computing in Design Optimization." The notebooks and supporting files demonstrate core quantum computing concepts, practical Qiskit workflows, and example applications in optimization and algorithm design.

## Table of Contents

1. [Set Up and Installation](./notebooks/install.ipynb) — A guided setup notebook that walks through environment preparation and package installation for running the examples locally.
2. [Basics of Qiskit](./notebooks/basics.ipynb) — A practical introduction to the Qiskit workflow (map → optimize → execute → post-process) with runnable examples using both local simulators and IBM Quantum backends.
3. [Single-Qubit Systems](./notebooks/single.ipynb) — Covers mathematical foundations for single-qubit states and gates including simple demonstrations.
4. [Multi-Qubit Systems](./notebooks/multi.ipynb) — Explains multi-qubit concepts and demonstrates phenomena such as entanglement, swap operations, Bell states, and the no-cloning theorem.
5. [Quantum Adder](./notebooks/adder.ipynb) — Demonstrates how to implement basic arithmetic (addition) using quantum gates and circuit constructions.
6. [Genetic Quantum Algorithm (GQA)](./notebooks/gqa.ipynb) — Demonstrates a hybrid genetic-quantum approach for combinatorial optimization (example: knapsack problem), illustrating how classical heuristics can be combined with quantum circuits.


## Quick start

1. Clone the repository:
    ```sh
    git clone https://github.com/Luxque/Quantum-Computing-in-Design-Optimization.git
    cd Quantum-Computing-in-Design-Optimization
    ```
2. Follow each instructions in [Set Up and Installation](./notebooks/install.ipynb) notebook.
3. Read and use the notebooks:
   * Launch JupyterLab or Jupyter Notebook and open files in the `notebooks/` directory.
   * Run cells in order. Some notebooks require API credentials to access IBM Quantum backends (see notes below).


## Notes on running on real quantum hardware

* To execute circuits on IBM Quantum systems you must provide your IBM Quantum API token and Cloud Resource Name (CRN). Keep these credentials private.
* Transpilation is required before submitting circuits to remote backends to ensure compatibility with the device’s native gates and topology.
* Expect queue times when using real hardware; results may differ from simulator output due to noise and device-specific characteristics.


## Contributing

You are more than welcome to contribute by helping fix any mistakes.
Please feel free to open an issue or submit a pull request to this repository.


## License

The Unlicense license.
