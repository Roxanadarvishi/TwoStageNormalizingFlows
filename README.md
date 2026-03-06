# TwoStageNormalizingFlows

This repository contains the code used to produce the simulation examples and the case study presented in the paper _Estimating Complex Densities using Two-Stage Normalizing Flows_ by Roxana Darvishi, David C. Stenning, and Owen G. Ward (Simon Fraser University). The repository includes the code used in Section 4 for the joint density inference simulations, the hierarchical model experiments with inaccessible likelihoods, and the astrophysics case study described in Section 5 of the paper.

The implementation is done in Python using PyTorch. The normalizing flow models used in the experiments rely primarily on the implementation provided in the repository by Vincent Stimper:
https://github.com/VincentStimper/normalizing-flows
This library provides the core flow components and training utilities used to construct and train the models in both stages of the proposed framework.

To run the code, clone the repository and install the required Python packages using the `requirements.txt` file. After installing the dependencies, the code can be executed directly to reproduce the experiments.

# Paper and Citation

LINK

If you use this code in your research, please cite the associated paper:

Darvishi, R., Stenning, D. C., & Ward, O. G.
Estimating Complex Densities using Two-Stage Normalizing Flows.

BibTeX here.

