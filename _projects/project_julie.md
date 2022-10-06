---
title: "Accelerating spin up of the ocean currents in climate simulations"
excerpt: "Collaboration between Julie Deshayes (LOCEAN), Martial Mancip (Maison de la Simulation), Redouane Lguensat (IPSL) and Nathan Cassereau (IDRIS)"
collection: portfolio
---

The objective is to study the acceleration of the equilibration of ocean currents in the IPSL global climate model (IPSLCM6). This equilibration phase also constrains the calibration of the parameters, and all of this ultimately represents 500% of the computational cost of the final simulations, used by scientific projects or by IPCC reports.  

The acceleration by artificial intelligence models deployed on Jean Zay computer should greatly reduce this initialization phase of the climate models, and facilitate changes in spatial resolution in particular. 

The idea is to have an AI inference model that extrapolates a series of simulation time steps (in months/years) and then reinjects the extrapolated solution into the climate model to perform new simulation steps. These two steps would be repeated as many times as necessary to obtain a stable algorithm that converges to a physically admissible solution comparable to full equilibria, while greatly reducing the number of time steps calculated explicitly with the model.   
