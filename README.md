# Reactor-Simulation
Reactor Simulation - Educational purpose
## Overview
Welcome to the Educational CFD and Reactor Simulation Project! This repository hosts educational materials, code samples, and simulation tools focused on the fascinating world of Computational Fluid Dynamics (CFD) applied to reactor simulations. This project aims to provide students, researchers, and enthusiasts with a hands-on learning experience in fluid dynamics, numerical simulations, and reactor behavior.

## Goals
The primary goals of this project are:

Educational Exploration: To offer an interactive learning platform for individuals interested in understanding Computational Fluid Dynamics principles and their application to reactor simulations.

Hands-on Experience: To provide practical examples, code templates, and simulation scenarios that users can work with to gain real-world experience in solving fluid flow problems.

Collaboration and Contribution: To encourage collaboration among the community by allowing contributors to submit enhancements, bug fixes, and additional simulation scenarios.

## Setup

Requirements

It is recommended to use mamba or miniconda

```
python
conda
```

Create a a new `conda` environment

```
conda env create --file conda/base.yaml 
```

Activate your environment

```
conda activate reactor-sim
```

Run locally

```
python src/reactor.py
```



convertToMeters 1;
vertices
(
    (0 0 0)
    (1 0 0)
    (1 1 0)
    (0 1 0)
    (0 0 1)
    (1 0 1)
    (1 1 1)
    (0 1 1)
);
blocks
(
    hex (0 1 2 3 4 5 6 7) (10 10 10) simpleGrading (1 1 1)
);
edges
(
    arc 0 1 (0.5 -0.5 0)
    arc 1 2