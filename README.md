# Master's Thesis: Quantum Simulation of Physical Problems Using the Ising-QUBO Framework: A Focus on Hydrogen Molecule Simulation

This repository contains the code and documentation associated with the Master's Thesis titled **Quantum Simulation of Physical Problems Using the Ising-QUBO Framework: A Focus on Hydrogen Molecule Simulation**.

## Project Description

The objective of this work is to illustrate how quantum computing is a highly useful tool for solving problems derived from the Ising model or QUBO-type problems. These types of problems are of great interest because, in addition to appearing in numerous fields such as logistics, economics, chemistry, or materials science, they are NP-hard problems when approached with classical computing, making them unsolvable exactly as the problem size grows .

Specifically, in this work, we will focus on how this framework allows us to tackle problems related to the characterization of molecular systems. These types of systems have different characteristics that we can model and simulate using quantum optimization algorithms and the Ising-QUBO formulation.

- Optimization of molecular geometry
- Search for the electronic configuration of a molecule
- Obtaining the ground state energy of a certain molecule

With these problems on the table, we will detail the physics that defines them and make use of the Ising-QUBO framework and the VQE algorithm to implement a computational solution to these problems. For this, we will use [Pennylane](https://pennylane.ai/), the software for programming quantum algorithms developed by the company [Xanadu](https://xanadu.ai/).


## Repository Structure

- `docs` Contains documentation related to the project, such as the final thesis report and other relevant documents.
- `notebooks`: Jupyter Notebooks for data analysis and visualization.
- `results`: Simulation results.
- `requirements.txt`: File listing Python dependencies required to run the project.
- `LICENSE`: License under which the project is distributed.

## Installation Requirements

To run the code in this project, you need to have Python installed along with the dependencies listed in the `requirements.txt` file. It is recommended to use a virtual environment to manage dependencies.

```bash
pip install -r requirements.txt
``` 
## Usage

To use this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies (see "Installation Requirements").
3. Explore the example code in the `notebooks` directory.
4. Analyze the results in the `results` directory.
5. Refer to the documentation in the `docs` directory for more details about the project and its operation.

## Contribution

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature/feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push your changes to your forked repository (`git push origin feature/feature-name`).
5. Make a pull request to this repository.

## License

This project is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
