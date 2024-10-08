[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

# Open quantum systems with qiskit

This set of notebooks contains the material for a comprehensive 54-hour course on open quantum systems (OQS), starting from basic concepts and covering the most essential concepts in the literature of OQS. Moreover, we present a novel idea: to teach how to simulate many paradigmatic examples of OQS dynamics with Qiskit and the IBM Q processors. This idea finds its origin in a recent publication ([García-Pérez, Rossi, Maniscalco, NPJ Quantum Inform. 6, 1 (2020)](https://www.nature.com/articles/s41534-019-0235-y)), in which we demonstrate that the IBM Q Experience is a versatile and robust platform for simulating open quantum systems.

The course is aimed at master students with a background in Quantum Mechanincs and Quantum Information theory who are also familiar with Qiskit. It is divided into lectures and projects. Throught the lecture notes, the lecturer will find several examples of important concepts for OQS in terms of circuits, with which we assume the student to be acquainted. The lecture material also includes many circuits that enable the simulation of OQS dynamics on the real IBM Q devices, with comprehensive explanations on their working principles. Finally, the lectures are to be supplemented with guided practical "hands-on" sessions in which the students must implement the corresponding circuits and analyze the results.

[Link to the website](https://qplaylearn.github.io/oqs-jupyterbook)

## Installation
In order to use the notebooks in the course and reproduce the results, clone the repository on your device and create a Python 3.11.10 environment with the method of choice (virtualenv, conda or poetry). For example, with poetry

```shell
poetry install
```

With pip,

```shell
pip install -r requirements.txt
```

## Usage

The notebooks are located in the `content` folder inside the repository.

----

Authors: Daria Anttila, Guillermo García-Pérez, Matteo Rossi, Boris Sokolov


This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
