## About 

Welcome to my GitHub page. 

I am a researcher currently working at the School of Geosciences of the University of Edinburgh. My research focuses on the interaction of agricultural ecosystems and the environment. I use mathematical modelling and data analytics to understand, describe and predict the movement of carbon and nitrogen in the plants in soil of agricultural ecosystems. 

You can find the articles, which I have authored, and the projects, in which I have participated, in [ResearchGate](https://www.researchgate.net/profile/Vasilis_Myrgiotis). Presented below is a list of the tools/scripts that I use and are available on GitHub. 

 - **DALEC-Grass** is a model of carbon biogeochemistry in managed grasslands. For its code see  [here](https://github.com/vmyrgiotis/DALEC_Grass). For a tutorial see [here](https://github.com/vmyrgiotis/DALEC_Grass).

- **Model-data fusion (MDF)** refers to the use of observations about a system in order to inform a model of that system about the system's actual state with the aim of improving the reliability of the model's predictions

<!---
Model-data fusion (MDF) refers to the use of various techniques through which observations about a system are used to inform a model of that system about the system's actual state with the aim of improving the reliability of the model's predictions. In the context of agroecosystem biogeochemistry, observed data are mostly snapshots of the above and/or below-ground concentration of nutrients, carbon, water etc. Such data are obtained by field sampling and the use of handheld/airborne/satellite sensors. Also, more temporally-continuous data on variables such as carbon dioxide and nitrous oxide fluxes can be obtained by flux tower and chamber-based measurment systems. The developed Bayesian MDF algorithm can use time-series of observations for any modelled variable to inform DALEC-Grass. Informing DALEC-Grass means refining the value range of its 33 parameters in order for the simulated data to fit with the observed data as good as possible. The Metropolis–Hastings algorithm is used to sample from multiple Markov chains. Samples that produce model outputs, which do not comply with basic ecological and biogeochemical rules are discarded.
---!> 

### Model evaluation  

I have developed and used a set of algorithms that can be used to assess how well a model predicts variables that are related to ecosystem functioning e.g. carbon/nitrogen fluxes, biomass etc. You can find a tutorial on these methods/algorithms 
[here](https://github.com/vmyrgiotis/model_evaluation_tutorial)
