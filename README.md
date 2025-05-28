# A Machine Learning-Driven, Probability-Based Approach to Enzyme Catalysis

# Sudip Das, Umberto Raucci, Enrico Trizio, Peilin Kang, Rui P. P. Neves, Maria J. Ramos, Michele Parrinello 

# https://doi.org/10.1021/acscatal.5c02431

This archive contains all the input files needed to reproduce the results of the paper.

For classical and QM/MM equilibrium MD simulations, please refer to PLUMED NEST repository with ID: 23.017

In the " Committor_Amylase_PLUMED_NEST" folder the following files are available:
- "Committor_training" folder contains a jupyter notebook file along with some example input data files for training the committor.
- "OPES_Enhanced_Sampling_with_Committor" folder contains all the CP2K, PLUMED and Pytorch input files to run OPES enhanced sampling QM/MM MD simulations with a smoother version of the committor. 

More information about using PLUMED with Pytorch can be found at https://github.com/luigibonati/data-driven-CVs.
More information about OPES can be found at https://github.com/invemichele/opes.
More information about Committor-OPES method can be found at https://github.com/EnricoTrizio/committor_2.0

The simulations were performed with GROMACS 2021.5, CP2K 9.1, PLUMED 2.9 and Pytorch 1.8. 

If you have comments or questions please send an email to das.sudip37@gmail.com
