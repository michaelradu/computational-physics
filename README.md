# Computational Physics (with Python)
### Overview
Welcome to the Computational Physics with Python repository! This collection of Jupyter notebooks is designed to explore and solve various computational physics problems, with a particular focus on modeling physical systems using numerical methods and Python.

### Key Features
- **Computational Models**: Includes models for various physical systems and phenomena, showcasing how numerical methods can be applied to solve real-world physics problems.
- **Numerical Solutions**: Solve ordinary differential equations (ODEs) using Python.
- **Educational Content**: Learn how computational techniques can be applied to classical physics problems.

## Getting Started
To get started with this repository, follow these instructions:

### Prerequisites
Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook or VSCode + Notebook Compatibility
- Required Python libraries: numpy, scipy, matplotlib

You can install the required libraries using pip:

```python
pip install numpy scipy matplotlib jupyter
```

or [conda](https://docs.anaconda.com/miniconda/) if you prefer.

### Cloning the Repository
Clone the repository to your local machine using:

```shell
git clone https://github.com/michaelradu/computational-physics
```

### Running the Notebooks
1. Navigate to the repository directory:

```shell
cd computational-physics
```

2. Start Jupyter Notebook (or VSCode):

```shell
jupyter notebook
```

3. Open the desired `.ipynb` file from the Jupyter interface and run the cells to explore the computational physics problems.

## Notebooks

- **Skydiving with Air Resistance**: This notebook models the skydiving problem, incorporating quadratic air friction. It demonstrates the application of numerical methods to solve ODEs and analyze the impact of air resistance on the skydiver's descent.
- **SIR Disease Model**: This notebook models the SIR (Susceptible, Infected, Recovered) disease model with additional dynamics for hospitalizations. It utilizes real-world data from the COVID-19 outbreak in Wuhan, China, to analyze disease progression and hospitalization effects. The notebook includes code implementation, visualizations, and a detailed explanation of the ODE derivations and results.

## Example
Here’s a brief overview of what you can find in the **Skydiving with Air Resistance** notebook:

- **Problem Formulation**: Introduction to the physics of skydiving with air resistance.
- **Mathematical Model**: Derivation of the differential equations describing the motion.
- **Numerical Solution**: Implementation of Python code to solve the equations and simulate the skydiver's descent.
- **Visualization**: Graphical representation of the results, including velocity and trajectory.

## Contributing
Contributions to this repository are welcome! To ensure consistency and quality, please adhere to the following guidelines:

### Directory Structure
Each contributed model should be organized in its own directory with the following structure:

```shell
SolutionName/
│
├── SolutionName.ipynb       # Jupyter Notebook containing the computational model
├── SolutionName.tex         # LaTeX source file for the PDF paper
├── SolutionName.pdf         # PDF paper following the standard format
└── SolutionName.md          # (Optional) Markdown file describing the solution
```

### Contribution Guidelines
1. **Jupyter Notebook (`.ipynb`)**: Include a well-documented Jupyter Notebook that contains the code for solving the computational problem. Ensure that the notebook includes explanations, code comments, and visualizations.

2. **LaTeX Document (`.tex`)**: Submit a LaTeX source file that is used to create the PDF paper. This document should be formatted according to the standard academic format and include all necessary sections (Abstract, Introduction, Methodology, Results, Discussion, Conclusion).

3. **PDF Paper (`.pdf`)**: Include the final PDF version of the paper generated from the LaTeX source. This should be a polished document that follows academic standards and includes all relevant sections.

4. **(Optional) Markdown File (`.md`)**: Provide a Markdown file that describes the solution in detail. This should include an overview of the problem, methodology, results, and any relevant discussions. **This is optional, but encouraged for effortless viewing within GitHub.**

### How to Submit a Contribution
1. Fork the repository and create a new branch for your contribution.
2. Add your solution as a new directory following the structure outlined above.
3. Ensure all files are properly named and formatted.
4. Submit a pull request with a clear description of your contribution.

### Guidelines Subject to Change
Please note that these contribution guidelines may be updated periodically. We encourage contributors to review the guidelines regularly to ensure compliance with the latest standards. Changes to the guidelines will be communicated through updates to this `README.md` file.

If you have any questions or need further clarification, please open an issue or contact us.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.