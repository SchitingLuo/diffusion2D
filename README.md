# diffusion2D

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Project description
This code solves the diffusion equation in 2D over a square domain which is at a certain temperature and a circular disc at the center which is at a higher temperature. This code solves the diffusion equation using the Finite Difference Method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.

## Installing the package

### Using pip3 to install from PyPI

```bash
pip install -i https://test.pypi.org/simple/ luosg-diffusion2d==0.0.1
```

### Required dependencies

- **Python** >= 3.6
- **NumPy**
- **Matplotlib**

## Running this package
Following Commands could be run in python Shell:
```python
>>> from luosg_diffusion2d import diffusion2d
>>> diffusion2d.solve()
```

## Citing
Instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).