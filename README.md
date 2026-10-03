# Biological Dynamical Systems

Academic Python notebooks exploring discrete population maps and compartmental differential equations through numerical simulation.

## Contents

| Notebook | Focus |
| --- | --- |
| [Bio mathematics (1).ipynb](Bio%20mathematics%20%281%29.ipynb) | Iterated maps and cobweb plots illustrating discrete dynamical behaviour. |
| [Bio-math2.ipynb](Bio-math2.ipynb) | Additional discrete-map and graphical dynamical-system exercises. |
| [Biomathematics_Assignment (2).ipynb](Biomathematics_Assignment%20%282%29.ipynb) | A three-compartment model: trajectories, phase portraits and threshold regimes. |
| [Bio-mathematics_Assign2 (1).ipynb](Bio-mathematics_Assign2%20%281%29.ipynb) | A four-compartment model with recruitment, transitions and loss terms. |

## Methods

NumPy supports numerical arrays and iteration; SciPy's `odeint` integrates compartmental ODEs; Matplotlib displays time series and two-/three-dimensional phase portraits.

These exercises connect model equations with qualitative dynamics, including equilibrium thresholds and the influence of initial conditions.

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook
```

Open a notebook, restart the kernel and run its cells in order. The notebooks specify their model parameters and initial conditions directly and do not read an external dataset.

## Scope

This is a collection of academic modelling exercises. It is distinct from the maintainer's master's research on age-structured hepatitis C and inverse parameter estimation. Parameter values illustrate mathematical behaviour; they are not presented as a fitted biological dataset.

A complete fresh-kernel execution record for this collection remains to be added.
