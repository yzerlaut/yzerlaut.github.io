**Welcome to the lab webpage !**

<div><img src="../docs/affiliation.svg" alt="profile" width="40%" align="left" style="margin-right: 10px"></div>

The lab was established following the creation of a _Junior Professor Chair in Computational Neuroscience_ at [Sorbonne Université](https://www.sorbonne-universite.fr/).
We perform our research at the [Paris Brain Institute (ICM)](https://institutducerveau-icm.org/) where we study the *mechanisms and principles of information processing in cortical networks* using theoretical and computational approaches.   
Our group is part of the [Rebola team](https://therebolalab.org) and we closely collaborate with the [Bacci team](https://baccilab.org). Together, we combine expertises in neurophysiological recordings (opto- and electrophysiology) and experimental manipulations (optogenetics, pharmacology, knockouts, ...) with our computational approaches to study cerebral processing and its dysfunctions.  

Check out our [openings](./openings.md) and do not hesitate to [contact us](mailto:yann.zerlaut@icm-institute.org) if you are interested in our work.

Here is a quick overview of the different aspects of our research:
  
## Theoretical Neuroscience

<div><img src="../docs/banner.svg" width="90%" align="center"></div>

We work on models of cortical processing at the synaptic, cellular, network and mesoscopic scale. 
We use analytical approaches together with numerical simulations to study the emergent computational properties of those systems. 
We give below a few examples of our theoretical work at different levels:
- spiking network dynamics: [7](./publications.md/#7), [8](./publications.md/#8), [5](./publications.md/#5), [4](./publications.md/#4)
- cortical microcircuits: [10](./publications.md/#10), [13](./publications.md/#13), [14](./publications.md/#14)  
- synaptic/cellular integration: [15](./publications.md/#15), [9](./publications.md/#9), [3](./publications.md/#3), [2](./publications.md/#2)  
- large scale models: [5](./publications.md/#5), [12](./publications.md/#12), [6](./publications.md/#6)

Check our [publication list](./publications.md) for more details.

## Data Science 

Our research strongly relies on the use of machine learning to analyze and interpret neurophysiological data. 

We design and implement multivariate models of neural activity from behavioral and sensory features (notably Generalized Linear Models). We use those models to (1) **extract functional principles in the healthy brain** and (2) **characterize functional deficits in disease models of brain activity**.
We also use various machine learning tools such as Artificial Neural Networks (ANNs) and dimensionality reduction techniques in the preprocessing of our neurophysiological and behavioral data.

## Open Science

Being strongly convinced that **open data and open source software is a major driver and a necessary condition for scientific progress**, we are commited to [Open Science](https://en.wikipedia.org/wiki/Open_science) in our research. 

In the era of data-intensive research, this however comes at the cost of important efforts during the research process. 
Data needs to be [standardised](https://www.nature.com/articles/sdata201618) and softwares need to be shared appropriately. 
We do spend a lot of energy in the design and implementation of such processes (see [Softwares](./softwares)).
All of the code and data of our research is made to be directly uploaded to modern research material platforms (such as [Ebrains](https://ebrains.eu)) independently from manuscript publication in scientific journals.

## Data Engineering

We do data-intensive research. Our experimental approach consists in recording neural activity in the neocortex using optical imaging (e.g. [2-photon calcium imaging](https://www.nature.com/articles/s43586-022-00147-1)) and electrophysiology (e.g. [Neuropixels probe recordings](https://www.science.org/doi/abs/10.1126/science.abf4588)) while monitoring behavior with video recordings. In practice, this means the processing and assembling of massive amounts of data on a daily basis. Part of our work consists in the design and maintenance of the preprocessing pipeline for such data.

## Software Engineering

Our original experimental approach and our data management strategy requires the development of custom softwares.

We develop [`physion`](https://github.com/yzerlaut/physion): a full software suite for neurophysiology in the context of visual processing in behaving mice. We also contributed to [`fairgraph`](https://fairgraph.readthedocs.io) a high-level API for metadata management in neuroscientific research. We develop several `python` packages for Data Science applications in the context of neurophysiology.

Our full software production is available on the Github profile: [github.com/yzerlaut](https://github.com/yzerlaut)

