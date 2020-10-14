---
title: "Revealing changes in global ocean circulation under global heating using machine learning"
excerpt: "Collaboration between Redouane Lguensat (CEA/LSCE/LOCEAN) and Maike Sonnewald (GFDL/Princeton University)"
collection: portfolio
---

The ocean is a key driver of climate; its circulation of waters is key to to storage of heat and carbon. Climate change will impact ocean circulation, but how and why is uncertain. Climate models from the Coupled Model Intercomparison (CMIP6) show a large spread, but saving enough data to know what dynamics cause the uncertainty is unfeasible due to the size of the CMIP6 ensemble.

In this project a machine learning workflow is developed that identifies interpretable dynamical ocean regimes in CMIP models. Based on *Sonnewald et al. 2019* using ECCO, unsupervised ML identified six ocean dynamical regimes in a 3D ocean model. These have distinct properties and provide a 2D rendition of the 3D physics.
The regimes serve as a large, labelled, dataset together with readily available CMIP data that can be used to train a supervised machine learning model. The goal then is to deploy it on CMIP6 models GFDL-ESM4 and GFDL-CM4 under a 4x abrupt CO2 increase scenario and investigate the results.
