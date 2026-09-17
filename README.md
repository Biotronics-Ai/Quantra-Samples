# Sample Notebooks for our Quantum Error Correction Framework - Quantra

A collection of sample notebooks demonstrating a **Quantum Error Correction (QEC) framework** across quantum machine learning, quantum kernels, quantum reinforcement learning, and well-known quantum algorithms.

The repository is designed to provide practical, reproducible examples of applying the error-correction framework to different quantum workloads and programming ecosystems.

## Overview

Quantum systems are inherently susceptible to noise and computational errors. This repository provides example implementations showing how our error-correction framework can be incorporated into different quantum computational workflows.

The current examples cover:

- Error-Corrected Quantum Machine Learning (QML)
- Error-Corrected Quantum Vectorization & Kernel Matrix computation
- Error-Corrected Quantum Reinforcement Learning (QRL)
- Shor's Algorithm Sample Implementations
- Grover's Algorithm Sample Implementations
- Quantum Key Distribution Sample Implementations

The goal of these notebooks is to demonstrate the framework across substantially different quantum workloads rather than limiting validation to a single circuit architecture or application domain.

> **Research status:** This repository contains experimental/research implementations. Results obtained in simulation or on particular quantum backends should not be interpreted as proof of fault-tolerant quantum computation on arbitrary hardware.

---

## Supported Quantum Frameworks

The current implementation and sample notebooks support three major Python quantum programming frameworks:

| Framework | Status |
|---|---|
| **PennyLane** | Supported |
| **Qiskit** | Supported |
| **Cirq** | Supported |

Where applicable, equivalent notebook implementations are provided for each framework so that the correction approach can be evaluated independently of a single quantum software stack.

---

## Sample Notebooks

### 1. Error-Corrected Quantum Machine Learning

Demonstrates the integration of the error-correction framework into a quantum machine learning workflow.

The notebooks can be used to investigate how correction affects training behavior, stability, convergence, and generalization under the experimental configuration.

Separate implementations are provided for **PennyLane, Cirq, and Qiskit**.

| Framework | Notebook | Run Online |
|---|---|---|
| PennyLane | `error_corrected_qml_pennylane.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
| Cirq | `error_corrected_qml_cirq.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
| Qiskit | `error_corrected_qml_qiskit.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |

---

### 2. Error-Corrected Quantum Vectorization & Kernel Matrix

Demonstrates error-corrected quantum vectorization and construction of a quantum kernel matrix.

This example focuses on quantum feature representations and pairwise kernel evaluation, providing a workload that differs substantially from conventional parameterized QML training.

Separate implementations are provided for **PennyLane, Cirq, and Qiskit**.

| Framework | Notebook | Run Online |
|---|---|---|
| PennyLane | `error_corrected_quantum_vectorization_kernel_matrix_pennylane.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
| Cirq | `error_corrected_quantum_vectorization_kernel_matrix_cirq.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
| Qiskit | `error_corrected_quantum_vectorization_kernel_matrix_qiskit.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |

---

### 3. Error-Corrected Quantum Reinforcement Learning

Demonstrates the application of the error-correction framework to a quantum reinforcement learning workflow.

These notebooks provide examples of correction operating in a learning environment where circuit outputs participate in an iterative decision and optimization process.

Separate implementations are provided for **PennyLane, Cirq, and Qiskit**.

| Framework | Notebook | Run Online |
|---|---|---|
| PennyLane | `error_corrected_quantum_reinforcement_learning_pennylane.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
| Cirq | `error_corrected_quantum_reinforcement_learning_cirq.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
| Qiskit | `error_corrected_quantum_reinforcement_learning_qiskit.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
---

### 4. Shor's Algorithm — Sample Implementations

Sample implementations demonstrating the framework in the context of **Shor's algorithm**.

Separate notebooks are provided for PennyLane, Cirq, and Qiskit.

| Framework | Notebook | Run Online |
|---|---|---|
| PennyLane | Shor's Algorithm — PennyLane | [Open in Kaggle](https://www.kaggle.com/) |
| Cirq | Shor's Algorithm — Cirq | [Open in Kaggle](https://www.kaggle.com/) |
| Qiskit | Shor's Algorithm — Qiskit | [Open in Kaggle](https://www.kaggle.com/) |

---

### 5. Grover's Algorithm — Sample Implementations

Sample implementations demonstrating the framework in the context of **Grover's search algorithm**.

Separate notebooks are provided for PennyLane, Cirq, and Qiskit.

| Framework | Notebook | Run Online |
|---|---|---|
| PennyLane | Grover's Algorithm — PennyLane | [Open in Kaggle](https://www.kaggle.com/) |
| Cirq | Grover's Algorithm — Cirq | [Open in Kaggle](https://www.kaggle.com/) |
| Qiskit | Grover's Algorithm — Qiskit | [Open in Kaggle](https://www.kaggle.com/) |

> The Kaggle URLs above currently point to the Kaggle homepage and are intended as placeholders. Replace each URL with the corresponding public notebook URL.

---

### 6. Quantum Key Distribution — Sample Implementations

Sample implementations demonstrating the error-correction framework in the context of **Quantum Key Distribution (QKD)**.

The notebooks implement a **BB84-based quantum key distribution workflow**, providing an example of the correction framework in a quantum communication and cryptographic setting.

Separate implementations are provided for **PennyLane, Cirq, and Qiskit**.

| Framework | Notebook | Run Online |
|---|---|---|
| PennyLane | `quantum_key_distribution_pennylane.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
| Cirq | `quantum_key_distribution_cirq.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |
| Qiskit | `quantum_key_distribution_qiskit.ipynb` | [Open in Kaggle](https://www.kaggle.com/) |

---

## Repository Structure

```text
.
├── README.md
├── error_corrected_qml/
│   ├── error_corrected_qml_pennylane.ipynb
│   ├── error_corrected_qml_cirq.ipynb
│   └── error_corrected_qml_qiskit.ipynb
│
├── error_corrected_quantum_vectorization_kernel_matrix/
│   ├── error_corrected_quantum_vectorization_kernel_matrix_pennylane.ipynb
│   ├── error_corrected_quantum_vectorization_kernel_matrix_cirq.ipynb
│   └── error_corrected_quantum_vectorization_kernel_matrix_qiskit.ipynb
│
├── error_corrected_quantum_reinforcement_learning/
│   ├── error_corrected_quantum_reinforcement_learning_pennylane.ipynb
│   ├── error_corrected_quantum_reinforcement_learning_cirq.ipynb
│   └── error_corrected_quantum_reinforcement_learning_qiskit.ipynb
│
├── shor/
│   ├── shor_pennylane.ipynb
│   ├── shor_cirq.ipynb
│   └── shor_qiskit.ipynb
│
├── grover/
│   ├── grover_pennylane.ipynb
│   ├── grover_cirq.ipynb
│   └── grover_qiskit.ipynb
│
├── quantum_key_distribution/
│   ├── quantum_key_distribution_pennylane.ipynb
│   ├── quantum_key_distribution_cirq.ipynb
│   └── quantum_key_distribution_qiskit.ipynb
│
└── LICENSE
```

---

## Running the Examples

The examples can be executed either locally through Jupyter or online through Kaggle.

For local execution:

```bash
pip install jupyter
jupyter notebook
```

Then open the desired notebook from the `notebooks/` directory.

For cloud execution, use the corresponding **Open in Kaggle** link in the tables above.

---

## Cross-Framework Design

A central objective of the repository is to demonstrate that the correction methodology is not restricted to one quantum programming library.

The three currently supported ecosystems expose quantum circuits through different abstractions and execution models:

**PennyLane** provides a differentiable quantum programming environment particularly suitable for hybrid quantum-classical machine learning.

**Qiskit** provides a broad quantum software stack for circuit construction, simulation, transpilation, and execution.

**Cirq** provides circuit-level abstractions with fine-grained control over quantum operations and simulation.

Providing implementations across these environments allows the framework to be studied under multiple software abstractions and quantum workloads.

---

## Experimental Validation

The notebooks are intended to make the behavior of the correction framework observable and reproducible.

Depending on the experiment, useful comparisons may include:

- corrected vs. uncorrected execution,
- noisy vs. reference execution,
- training and validation behavior,
- circuit-level observables,
- correction activity,
- kernel stability,
- learning convergence,
- task-level performance,
- and behavior across different noise configurations.

For meaningful evaluation, correction should be treated as an experimental variable rather than assuming that improved downstream task performance alone establishes the source of the improvement.

Where supported by the notebook, ablation experiments with correction disabled can therefore provide an important control.

---

## Future Work

Future development will focus on expanding both the range of supported quantum software ecosystems and the diversity of validation workloads.

Potential additional Python quantum programming environments include:

- **Amazon Braket SDK**
- **NVIDIA CUDA-Q**
- **Rigetti pyQuil**
- **ProjectQ**
- additional hardware-specific or simulator-specific backends

Further work may also include broader noise models, additional correction strategies, hardware experiments, larger circuits, automated cross-framework benchmarking, and systematic corrected-vs-uncorrected ablation studies.

The long-term objective is to maintain a framework-independent interface that allows the same correction methodology to be evaluated across different quantum programming environments and execution backends.

---

## Reproducibility

Reproducibility is a primary purpose of this repository.

Whenever possible, experiments should document:

- quantum framework and version,
- simulator or hardware backend,
- number of qubits,
- circuit depth and architecture,
- noise model and parameters,
- correction configuration,
- random seeds,
- optimization settings,
- dataset or environment configuration,
- and corrected/uncorrected control results.

This information is particularly important when comparing results across PennyLane, Cirq, and Qiskit because differences in simulators, transpilation, measurement conventions, and backend behavior can affect experimental outcomes.

---

## Citation

If you use this framework or the sample implementations in academic work, please cite the associated publication once the citation information is available.

```bibtex
@article{quantum_error_correction_framework,
  title   = {Quantum Error Correction Framework},
  author  = {<AUTHOR(S)>},
  year    = {<YEAR>},
  journal = {<JOURNAL / PREPRINT SERVER>},
  doi     = {<DOI>}
}
```

The citation block above is a placeholder and should be updated with the final publication metadata.

---

## Contributing

Contributions, reproducibility tests, additional backend implementations, and independent validation experiments are welcome.

Particularly useful contributions include:

- implementations for additional quantum programming frameworks,
- alternative noise models,
- additional algorithm demonstrations,
- corrected-vs-uncorrected benchmarks,
- hardware-backend experiments,
- and reproducibility studies across different simulators.

---

## Disclaimer

This repository is intended for **research, experimentation, and education**.

The included implementations and experimental results should not be interpreted as guarantees of hardware-level fault tolerance or universal error correction. Performance and correction behavior may depend on the circuit, backend, simulator, noise model, hyperparameters, and experimental conditions.

---

## License

See the repository's `LICENSE` file for licensing terms.
