# GLEE_Simulations_Seismology
This repository contains simulations for the seismology payload of GLEE system of IITBSSP. The software used here is devito.

The simple simulation uses the inbuilt method model directly to get a quick understanding.This is an acoustic model however, our final aim is for an elastic model.

The simulation with boundary conditions is actually the final model required for answering the questions for feasibility. It implements rigorious boundary conditions using subdomains. This too is an acoustic model.

The elastic models have been constructed using three different ways:

1. Using the model object of devito and setting parameters required.
2. Using subdomains
3. Using the demo_model of devito and modifying the parameters according to our requirements
