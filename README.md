# On the Computation of ReLU-based RNNs equivalent to CPWA models of Dynamical Systems and vice versa
![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)
![IFAC World Congress](https://img.shields.io/badge/Accepted%20@-IFAC%20World%20Congress%202026-blue)

Official code for the paper: **"Recurrent Neural Networks with ReLU activations are Continuous Piecewise Affine Systems Dynamical Systems and Viceversa"**

Authors:
- Marco Ledda, PhD Student
- Diego Deplano, Researcher
- Alessandro Giua, Full Professor
- Mauro Franceschelli, Associate Professor

_All authors are with the DIEE, University of Cagliari, 09123 Cagliari, Italy._

---

## 📝 Abstract
> This paper develops computational procedures to translate between ReLU recurrent neural networks (RNNs) and continuous piecewise-affine (CPWA) dynamical systems. We show that every ReLU RNN induces a finite polyhedral partition of the state–input space with affine dynamics on each region and provide an explicit constructive algorithm to compute its corresponding CPWA representation. Conversely, we show that every CPWA dynamical system admits an exact realization as a ReLU RNN and provide a constructive procedure to compute the associated network parameters. The computational procedures are illustrated by numerical examples for both directions, showcasing exactly matching trajectories and validating the implementation of the proposed transformations.


## 🚀 Getting Started

### Prerequisites

- **Python** 3.10 or higher  
- **Matplotlib** 3.10.1 or higher  
- **NumPy** 2.1.3 or higher  
- **SciPy** 1.15.2 or higher

### 1. Clone the repository
First of all, you will need to clone this repository. To do this, run the following command:

```bash
git clone https://github.com/mledda17/recurrent_nn_pwa.git
```

### 2. Install requirements and dependecies
Install dependencies via:

```bash
pip install -r requirements.txt
```

### 3. Run numerical validation
All experiments can be executed using the following command:
```bash
python scripts/simulate_compare.py
```

The results of the experiments will be put in a new folder "scripts/plots".

Official code for the paper: **"Recurrent Neural Networks with ReLU activations are Continuous Piecewise Affine Systems Dynamical Systems and Viceversa"**  
