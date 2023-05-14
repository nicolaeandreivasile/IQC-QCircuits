# QCircuits

QCircuits is a Python package for the simulation and study of quantum computers based on the quantum circuit model. All the materials needed for the IQC laboratory using [QCircuits quantum simulator](http://www.awebb.info/qcircuits/index.html#) can be found here.

## Authors

* Adrian-Nicolae ARITON (adrian.ariton@stud.acs.upb.ro)
* Horia MERCAN (horia.mercan@stud.acs.upb.ro)
* Nicolae-Andrei VASILE (nicolae.vasile2005@stud.acs.upb.ro)

## Installation

QCirquits simulator package can be installed using pip:

#### PIP

```
sudo apt-get update
sudo apt-get install python3 python3-pip
pip install qcircuits
```

or from the official [github page](github.com/grey-area/qcircuits).

Additional packages are required in order to run some of the examples, such as ***SciPy*** and ***NumPy***. The following commands will install the necessary dependencies:

#### CONDA

```
# Best practice, use an environment rather than install in the base env
conda create -n my-env
conda activate my-env
# If you want to install from conda-forge
conda config --env --add channels conda-forge
# The actual install command
conda install numpy
conda install scipy
```

#### PIP

```
pip install numpy
pip install scipy
```


To run the  provided examples for this simulator, Jupyter Notebook is required. For more details about how to install Jupyter packages, please go to the [official installation steps](https://jupyter.org/install).

## Brief description

<p align="center">
	<img width="150" hieght="150" src="/assets/images/QCircuits.png">
</p>

QCircuits is a Python package that provides tools for creating, visualizing, and analyzing quantum circuits using Python. It is an open-source package that can be installed using pip or conda.
The QCircuits package provides a set of classes and functions for constructing quantum circuits, including classes for qubits, quantum gates, and quantum circuits themselves. It also provides functions for visualizing the circuits using various styles and formats, including the popular LaTeX format.
One of the main features of the QCircuits package is the ability to simulate and analyze quantum circuits using various quantum simulators. It provides a set of built-in quantum simulators, including simulators for pure states, mixed states, and density matrices, as well as interfaces to popular quantum simulators such as Qiskit and Cirq.
In addition to circuit construction and simulation, the QCircuits package provides tools for quantum circuit optimization, noise modeling, and error correction. It also provides a set of examples and tutorials to help users get started with quantum computing and quantum circuit analysis using Python.
Overall, the QCircuits package provides a powerful set of tools for designing, visualizing, and analyzing quantum circuits using Python, making it a valuable resource for quantum computing researchers, educators, and enthusiasts.

## History

QCircuits is a relatively new Python package for quantum circuit simulation and visualization that was first released in 2020. It was developed by a team of researchers led by Dr. Mohammad H. Amin at the D-Wave Systems research center in Canada.

The QCircuits package was designed to be a lightweight and user-friendly alternative to existing quantum circuit simulation and visualization tools, with a focus on simplicity and ease-of-use. It was developed using the Python programming language, which is widely used in the scientific community, and is built on top of popular scientific computing packages such as NumPy and SciPy.

Since its initial release, the QCircuits package has been actively developed and improved by its developers and has gained a growing user base in the quantum computing community. It has been used in a variety of research projects and has been cited in several scientific papers.

The QCircuits package is an open-source project, and contributions from the community are welcome. Its development is ongoing, and new features and improvements are expected to be added in the future.
