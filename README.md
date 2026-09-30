# RAxML
RAxML for Phylogeny

RAxML-NG is a phylogenetic tree inference tool which uses maximum-likelihood (ML) optimality criterion. Its search heuristic is based on iteratively performing a series of Subtree Pruning and Regrafting (SPR) moves, which allows to quickly navigate to the best-known ML tree. RAxML-NG is a successor of RAxML (Stamatakis 2014) and leverages the highly optimized likelihood computation implemented in coraxlib.

RAxML-NG offers improvements in speed, flexibility and user-friendliness over the previous RAxML versions. It also implements some of the features previously available in ExaML (Kozlov et al. 2015), including checkpointing and efficient load balancing for partitioned alignments (Kobert et al. 2014). RAxML-NG version 2.0 offers a plethora of new features such as adaptive search heuristics, automatic model selection, and fast branch support metrics.

Documentation: github wiki

This code is for running RAxML in a High Performance Computing Environment

Note: The core genome alignment file should be generated using the Roary Program
