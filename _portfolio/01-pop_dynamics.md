---
title: "Population dynamics (python)"
excerpt: "Python library to conduct experiments in population dynamics.<br/><img src='/images/predator_prey.png'>"
collection: portfolio
---

Github repository: [https://github.com/quiet-minds/population-dynamics](https://github.com/quiet-minds/population-dynamics)

Library to conduct experiements on population dynamics.

![Lotka-Volterra predator-prey system](/images/predator_prey.png)

## Installation

1. Create conda environment
```
conda env create -f environment.yml
```
2. Activate the environment
```
source activate population-dynamics
```
3. Install `causal` as a package within the environment
```
python install_causal.py develop
```
4. To setup all the log and results folders, run
```
bash setup.sh
```