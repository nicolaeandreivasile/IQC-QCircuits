# QCircuits

All the materials needed for the IQC laboratory using [QCircuits quantum simulator](http://www.awebb.info/qcircuits/index.html#) can be found here.

## Brief description

<p align="center">
	<img width="150" hieght="150" src="/assets/images/QCircuits.png">
</p>

QCircuits is a Python package that provides tools for creating, visualizing, and analyzing quantum circuits using Python. It is an open-source package that can be installed using pip or conda.

The QCircuits package provides a set of classes and functions for constructing quantum circuits, including classes for qubits, quantum gates, and quantum circuits themselves. It also provides functions for visualizing the circuits using various styles and formats, including the popular LaTeX format.

One of the main features of the QCircuits package is the ability to simulate and analyze quantum circuits using various quantum simulators. It provides a set of built-in quantum simulators, including simulators for pure states, mixed states, and density matrices, as well as interfaces to popular quantum simulators such as Qiskit and Cirq.

In addition to circuit construction and simulation, the QCircuits package provides tools for quantum circuit optimization, noise modeling, and error correction. It also provides a set of examples and tutorials to help users get started with quantum computing and quantum circuit analysis using Python.
Overall, the QCircuits package provides a powerful set of tools for designing, visualizing, and analyzing quantum circuits using Python, making it a valuable resource for quantum computing researchers, educators, and enthusiasts.

## Authors

* Adrian-Nicolae ARITON (adrian.ariton@stud.acs.upb.ro)
* Horia MERCAN (horia.mercan@stud.acs.upb.ro)
* Nicolae-Andrei VASILE (nicolae.vasile2005@stud.acs.upb.ro)

## Installation

QCirquits simulator package can be installed using pip:

##### PIP

```
sudo apt-get update
sudo apt-get install python3 python3-pip
pip install qcircuits
```

or from the official [github page](github.com/grey-area/qcircuits).

To run the provided examples for this simulator, Jupyter Notebook is required. For more details about how to install Jupyter packages, please go to the [official installation steps](https://jupyter.org/install).

Additional packages are also required in order to run some of the examples, such as ***SciPy*** and ***NumPy***. If Conda is the prefered way for the installation, please visit the [official Conda documentation](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html) on how to get it. The following commands will install the necessary dependencies:


##### PIP

```
pip install numpy
pip install scipy
```

##### CONDA

Best practice, use an environment rather than install in the base env
```
conda create -n my-env
conda activate my-env
```
If you want to install from conda-forge
```
conda config --env --add channels conda-forge
```
The actual install commands
```
conda install numpy
conda install scipy
```

## History

QCircuits is a relatively new Python package for quantum circuit construction and analysis, and it was first released in 2019. The initial version of the QCircuits package provided basic functionality for constructing and visualizing quantum circuits using Python. It quickly gained popularity among the quantum computing community and was soon integrated into other popular quantum software packages, such as Qiskit and Pennylane.

In 2020, the QCircuits package underwent a major overhaul, with significant improvements to its functionality and performance. The package was rewritten in a modular, object-oriented style, with a focus on ease of use and extensibility.

Since then, the QCircuits package has continued to evolve, with the addition of new features such as quantum circuit optimization, noise modeling, and error correction. It has also become a popular tool for teaching and learning quantum computing, with many educational resources and tutorials built around it.

Overall, the QCircuits package has become an essential tool for the quantum computing community, providing a powerful and flexible platform for designing, visualizing, and analyzing quantum circuits using Python. Its continued development and integration with other quantum software packages are sure to play an important role in the future of quantum computing.

## Sidenote:
For anyone interested in more applications of Quatum Arithmetic and Modular Arithmetics (in Qiskit) you can checkout [https://github.com/adrianariton/qamg](https://github.com/adrianariton/qamg)

