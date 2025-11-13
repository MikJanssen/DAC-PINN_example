# DAC-PINN_example for Capgemini interview

## Overview 
This project shows code snippets from the creation of a physics-informed neural network  (PINN) used for solving a coupled system of partial differential equations (PDEs). The goal of solving these equations is to predict the concentration gradient of different species through a reactor in space and time.
The repository contains an example jupyter notebook with snippets from the original code used to conduct the research for my master thesis. Parts of the code are replaced with text and only some relevent results are shown as pictures.
This notebook is designed to show a conceptual representation of my coding level, and not for full deployment.
Due to confidentiality reasons no data is supplied.

## Requirements
To run the full program, you need a basic Python environment (source code is written in Python 3.14.0) with Jupyter notebook installed.
The following Python libraries are used in the full program:
- numpy
- pandas
- scipy
- matplotlib
- scipy
- torch
- scikit-learn
- pyDOE

### The external packages can be installed with:
```bash
pip install numpy pandas matplotlib scipy torch scikit-learn pyDOE