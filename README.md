# Simulation of a crack growth in a thick square plate based on Peridynamic Theory

Silling, S. A., & Askari, E. (2005). *A meshfree method based on the peridynamic model of solid mechanics*. *Computers & Structures, 83*(17-18), 1526-1535. https://doi.org/10.1016/j.compstruc.2004.11.026

Author: Syed Talha Tirmizi (@s-tirmizi)

This repository contains a Jupyter Notebook implementing Peridynamic Theory, an alternative framework for solid mechanics. Unlike traditional methods that rely on partial differential equations, peridynamics uses integral equations to model interactions between particles over finite distances, capturing fracture and damage as a natural outcome of the governing equations.

Features:

- Peridynamic Formulation: Step-by-step implementation of the peridynamic approach, including constitutive models and interaction functions.
- Damage Modeling: Simulate fracture and damage evolution directly from the equations of motion.
- Parameter Flexibility: Easily modify parameters like particle spacing, interaction horizons, and material properties.
- Data Visualization: Generate plots and animations to analyze the results and gain deeper insights into material behavior.

This repository is a great resource for researchers, students, and coders interested in computational mechanics, fracture modeling, and peridynamic simulations. Contributions and suggestions are welcome!

Below is a visualization from the simulation:

<div align="center">
    <img src="https://github.com/s-tirmizi/peridynamics-model/blob/main/dec_scatter_plot_animation-dpi50.gif" alt="Crack Growth Simulation" width="600">
    <p><i>Figure: Fracture propragation in a 2D square plate.</i></p>
</div>
