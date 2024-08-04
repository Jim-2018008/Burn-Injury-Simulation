
# Burn Injury Simulation

This project focuses on simulating burn injuries in blood-perfused skin using COMSOL Multiphysics. It includes step-by-step instructions for setting up the model, defining parameters, meshing, and postprocessing to analyze burn injuries.

## Table of Contents
- [Introduction](#introduction)
- [Model Setup](#model-setup)
  - [Geometry Creation](#geometry-creation)
  - [Material Selection](#material-selection)
- [Defining Parameters](#defining-parameters)
- [Meshing](#meshing)
- [Solver Settings and Solution](#solver-settings-and-solution)
- [Postprocessing](#postprocessing)
- [References](#references)
- [Contact](#contact)

## Introduction
Burn injuries are a critical area of study in biomedical engineering. This project aims to simulate burn injuries in blood-perfused skin using COMSOL Multiphysics to understand the thermal and physiological responses of skin to burns.

## Model Setup

### Geometry Creation
1. Open COMSOL Multiphysics and select Model Wizard.
2. Select 2D Axisymmetric space dimension.
3. Under Heat Transfer module, select Heat Transfer in Solids (ht).
4. Add General Form PDE from Mathematics > PDE Interfaces.
5. Select Time Dependent study.

### Material Selection
1. Create materials for Subcutaneous fat, Dermis, and Epidermis.
2. Assign the materials to respective domains.

## Defining Parameters
1. Set parameters for blood perfusion and other thermal properties.
2. Define heat sources and initial conditions.

## Meshing
1. Use a mapped mesh with specific element distributions for different boundaries.
2. Adjust mesh properties to ensure accuracy.

## Solver Settings and Solution
1. Set the time range for the simulation.
2. Compute the solution to obtain temperature and burn injury data.

## Postprocessing
1. Create contour plots for temperature and burn injury levels.
2. Analyze the results to understand the effects of burns on skin tissue.

## References
1. Datta, Ashim, and Vineet Rakesh. *An introduction to modeling of transport processes: applications to biomedical systems*. Cambridge University Press, 2010.
2. Dokos, Socrates. *Modelling Organs, Tissues, Cells and Devices: Using MATLAB and COMSOL Multiphysics*. Springer, 2017.
3. Diller, K. R., and L. J. Hayes. "A finite element model of burn injury in blood-perfused skin." *Journal of biomechanical engineering* 105.3 (1983): 300-307.

## Contact
For further information or inquiries, please contact:

Nafish Ahanaf  
Email: [er.nafish.ahanaf@gmail.com](mailto:er.nafish.ahanaf@gmail.com)

---
