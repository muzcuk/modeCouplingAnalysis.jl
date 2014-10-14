# modeCouplingAnalysis

This is a julia framework to perform mode coupling analysis as described in this (http://arxiv.org/pdf/1310.8598.pdf) paper. 

It was designed to provide an infrastructure for possible implementations of other analyses on protein dynamics. 

# protein type

This is a type that keeps a MD trajectory for a protein. Some pre-processing is necessary on the original trajectory.

## preprocessing of trajectory

load your trajectory (using vmd, pymol etc.)

- We will only use alpha carbons (name CA) so you should generate a trimmed down 

- Is accomplished by preprocess.awk script
