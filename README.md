# Imaging Service Simulation

data604_final

by Jean Jimenez

For CUNY SPS Summer 2024

## Project Overview

This repository contains the final project for the Data 604 course at CUNY SPS, Summer 2024, completed by Jean Jimenez. The project involves simulating outpatient radiology imaging services using the SimPy library to model waiting times and optimize the process. The goal is to minimize patient wait times from registration to receiving results.

## Files in the Repository

1. [jjimenez_imaging_service_simulation.pdf](https://github.com/sleepysloth12/data604_final/blob/d35b9bb0df8e3237cd57d164c4d6cab5e0648fb6/jjimenez_imaging_service_simulation.pdf) - A detailed document outlining the simulation, methodology, and findings.
2. [jjimenez_imaging_service_simulation.ipynb](https://github.com/sleepysloth12/data604_final/blob/d35b9bb0df8e3237cd57d164c4d6cab5e0648fb6/jjimenez_imaging_service_simulation.ipynb) - The Jupyter Notebook containing the simulation code.
3. [jjimenez_604_final.pptx](https://github.com/sleepysloth12/data604_final/blob/d35b9bb0df8e3237cd57d164c4d6cab5e0648fb6/jjimenez_604_final.pptx) - The PowerPoint presentation summarizing the project and its findings.
4. [jjimenez_604Final_supplemental.pdf](https://github.com/sleepysloth12/data604_final/blob/d35b9bb0df8e3237cd57d164c4d6cab5e0648fb6/jjimenez_604Final_supplemental.pdf) - Supplemental document with flowchart and tables of parameters used in the simulation.

## Assignment Instructions

The project involved creating a discrete event simulation using SimPy, focusing on the following elements:

1. **State the Problem and Its Significance**
2. **Provide a Flow-Chart Model**
3. **Simulate the Process for Appropriate Iterations**
4. **Justify the Validity of the Model**
5. **State Conclusions and Findings**
6. **Generate Appropriate Graphs**

## What was done

I create a scenario involving a patient undergoing an abdomen MRI scan, highlighting the importance of minimizing wait times in outpatient imaging services.


A simulation was developed using Python and the SimPy package. It includes:
- Initialization of environment and variables
- Estimation of scan acquisition and interpretation times
- Modeling of patient arrival, registration, scanning, and interpretation processes


An optimization phase was conducted to find the optimal number of machines and staff for each imaging office, using the L-BFGS-B method to minimize patient wait times.


The model was validated using generated data, with metrics such as mean squared error (MSE) and mean absolute error (MAE) used to compare the simulated data against an M/M/1 queueing model.



---

**Works Cited**

- Poyiadji, N., et al. (2023). *Diagnostic imaging utilization in the emergency department: Recent trends in volume and radiology work relative value units*. Journal of the American College of Radiology, 20(12), 1207-1214. DOI: [10.1016/j.jacr.2023.06.012](https://doi.org/10.1016/j.jacr.2023.06.012)
- Duszak, R., et al. (2020). *Characteristics of COVID-19 community practice declines in noninvasive diagnostic imaging professional work*. Journal of the American College of Radiology, 17(11), 1453-1459. DOI: [10.1016/j.jacr.2020.08.001](https://doi.org/10.1016/j.jacr.2020.08.001)
- Downey, A. B. (2017). *Modeling and simulation in Python (Version 3.4.3)*. Green Tea Press. [Green Tea Press](https://greenteapress.com/ModSimPy3)

---
