---
title: "Accelerating spin up of the ocean currents in climate simulations"
excerpt: "Collaboration between Julie Deshayes (LOCEAN), Martial Mancip (Maison de la Simulation), Redouane Lguensat (IPSL), Nathan Cassereau (IDRIS) and Guillaume Gachon (ENS Lyon)"
collection: portfolio
---

The objective is to study the acceleration of the equilibration of ocean currents in the IPSL global climate model (IPSLCM6). This equilibration phase also constrains the calibration of the parameters, and all of this ultimately represents 500% of the computational cost of the final simulations, used by scientific projects or by IPCC reports.  

The first achievement of this project is to demonstrate the feasibility of accelerating the equilibrium of the barotropic (i.e. vertically homogeneous) component of the NEMO ocean currents of the IPSL climate model. This achievement requires the use of data science tools (advanced statistics, ML), an emerging perspective in climate modelling. 

The idea is to have an AI inference model that extrapolates a series of simulation time steps (in months/years) and then reinjects the extrapolated solution into the climate model to perform new simulation steps. These two steps would be repeated as many times as necessary to obtain a stable algorithm that converges to a physically admissible solution comparable to full equilibria, while greatly reducing the number of time steps calculated explicitly with the model. 

The reduction of explicit calculation time by the climate model (operated under CPU), which is more costly than inference by Data Science techniques (performed under GPU), leads to an improvement in the numerical calculation frugality of climate modelling. 

In addition, acceleration of spinup generates a variety of admissible accelerated states (with respect to the existing database) which provides an ensemblistic dimension for the climate model in question. This will allow direct and efficient use of uncertainty quantification techniques to estimate the intrinsic uncertainty of future climate projections.

To know more about this project, visit ![https://github.com/Maison-de-la-Simulation/hrmes](https://github.com/Maison-de-la-Simulation/hrmes) : this repository includes ![a Concept note that includes results](https://github.com/Maison-de-la-Simulation/hrmes/blob/master/concept/concept.md), ![Meeting notes (in French)](https://github.com/Maison-de-la-Simulation/hrmes/blob/master/Meetings/meeting.md), and all codes...

Fore more information, email ![Julie Deshayes](mailto:julie.deshayes@locean.ipsl.fr).


