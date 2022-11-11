<!-- Badges: -->
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?logo=paypal&style=flat-square)](https://www.paypal.me/CamponogaraViera/100)
[![License](https://img.shields.io/github/license/QuCAI-Lab/qiskit2022-global-summer-school.svg?logo=CreativeCommons&style=flat-square)](https://github.com/QuCAI-Lab/qiskit2022-global-summer-school/blob/dev/LICENSE.md)
[![Contributions](https://img.shields.io/badge/contributions-welcome-orange?style=flat-square)](https://github.com/QuCAI-Lab/qiskit2022-global-summer-school/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/QuCAI-Lab/qiskit2022-global-summer-school/graphs/commit-activity)
[![Release](https://img.shields.io/github/release/QuCAI-Lab/qiskit2022-global-summer-school.svg)](https://github.com/QuCAI-Lab/qiskit2022-global-summer-school/releases)

<!-- Logo: -->
<div align="center">
  <a href="https://qucai-lab.github.io/">
    <img src="https://github.com/QuCAI-Lab/qucai-lab.github.io/blob/main/assets/QuCAI-Lab.png" height="500" width="500" alt="Logo">
  </a>
</div>

<!-- Title: -->
<div align="center">
  <h1> <a href="https://qiskit.org/events/summer-school/"> Qiskit Global Summer School 2022 </a></h1>
  <h2> Solutions to the Lab exercises </h2>
</div>
<br> 
<br> 

<!-- Author: -->
<div align="center">
<b>Author:<a target="_blank" href="https://github.com/camponogaraviera"> ¹Lucas Camponogara Viera</a></b>
<br>
<b><a target="_blank" href="https://en.ntnu.edu.tw/">¹National Taiwan Normal University - NTNU, Taipei, Taiwan</a></b>.
</div>

<!-- Dependencies: -->
# Dependencies
<code>
<a href="https://www.python.org/" target="_blank" rel="noopener noreferrer"><img height="27" src="https://www.python.org/static/img/python-logo.png"></a>
<a href="https://numpy.org/" target="_blank" rel="noopener noreferrer"><img height="27" src="https://numpy.org/images/logo.svg"></a>
<a href="https://matplotlib.org" target="_blank" rel="noopener noreferrer"><img height="27" src="https://matplotlib.org/_static/images/logo2.svg"></a>
<a href="https://qiskit.org/" target="_blank" rel="noopener noreferrer">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://qiskit.org/documentation/stable/0.19/_static/logo.png">
    <img alt="Shows Qiskit logo for light color mode and dark color mode." src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Qiskit-Logo.svg/1200px-Qiskit-Logo.svg.png" height="27">
  </picture>
</a>
</code>
<br>
<br>
  
For specific versions, see the [environment.yml](environment.yml) file.

# Description

This repository features the submitted solutions and a [supplementary.ipynb](supplementary.ipynb) material.


# Table of Contents

- **[solution_lab1](https://github.com/QuCAI-Lab/qiskit2022-global-summer-school/blob/dev/solution_lab1.ipynb)**
  - Introduction to Qiskit: 
    - single-qubit gates, multi-qubit gates, Bell states, GHZ-like states, and measurement.
  - Quantum Circuits and Complexity: 
    - circuit depth, complexity, and fully entangled states.
- **[solution_lab2](https://github.com/QuCAI-Lab/qiskit2022-global-summer-school/blob/dev/solution_lab2.ipynb)**
  - Advanced Circuits: 
    - operators, Qiskit Opflow, and time-evolution under the tight binding Hamiltonian.
- **[solution_lab3](https://github.com/QuCAI-Lab/qiskit2022-global-summer-school/blob/dev/solution_lab3.ipynb)**
  - Quantum Noise: 
    - projection noise, measurement noise, coherent noise, and incoherent noise.
- **[solution_lab4](https://github.com/QuCAI-Lab/qiskit2022-global-summer-school/blob/dev/solution_lab4.ipynb)**
  - Quantum Simulation:
    - the XXX Heisenberg model Hamiltonian.
  - Optimal Time Evolution Contest:
    - time evolving the state $|110\rangle$ to $t=\pi$ under the XXX Heisenberg model Hamiltonian.

# First steps to run locally

- Note: install the [IBM grading client](https://github.com/qiskit-community/Quantum-Challenge-Grader#run-locally) to run all notebooks successfully.

Clone this repository:
```bash
git clone https://github.com/QuCAI-Lab/qiskit2022-global-summer-school.git && cd qiskit2022-global-summer-school
```
Create a conda environment with the required dependencies:
```bash
conda env create -n qiskitschool2022 environment.yml && conda activate qiskitschool2022
```
Install pip:
```bash
conda install -yc conda-forge pip==22.3.1 && python3 -m pip install -U --upgrade pip
```
Installing qiskit[all]:
```bash
python3 -m pip install -U qiskit[all]
```
To check if qiskit is installed, run `$conda list qiskit` or `$ pip show qiskit` or `$ python3 -m pip show qiskit`. 

Final step, installing qiskit-textbook:
```bash
pip install git+https://github.com/qiskit-community/qiskit-textbook.git#subdirectory=qiskit-textbook-src
```

# References &nbsp; <a href="#"><img valign="middle" height="45px" src="https://img.icons8.com/book" width="45" hspace="0px" vspace="0px"></a> 
  
\[1] [Qiskit Global Summer School 2022](https://www.youtube.com/playlist?list=PLOFEBzvs-Vvo5o97bYt8o1l8Ra1poMASQ).

 
# License

This work is licensed under a [Creative Commons Zero v1.0 Universal](LICENSE.md) license.

<hr>

Created and maintained by [@camponogaraviera][1].

[1]: https://github.com/camponogaraviera