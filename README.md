A Hybrid Parallel Implementation of the Aho-Corasick and Wu-Manber Algorithms Using NVIDIA CUDA and MPI Evaluated on a Biological Sequence Database. Charalampos S. Kouzinopoulos, John-Alexander M. Assael, Themistoklis K. Pyrgiotis, and Konstantinos G. Margaritis

Charalampos S. Kouzinopoulos, John-Alexander M. Assael, Themistoklis K. Pyrgiotis, Konstantinos G. Margaritis

==================

http://arxiv.org/abs/1407.2889


Multiple matching algorithms are used to locate the occurrences of patterns from a finite pattern set in a large input string. Aho-Corasick and Wu-Manber, two of the most well known algorithms for multiple matching require an increased computing power, particularly in cases where large-size datasets must be processed, as is common in computational biology applications. Over the past years, Graphics Processing Units (GPUs) have evolved to powerful parallel processors outperforming Central Processing Units (CPUs) in scientific calculations. Moreover, multiple GPUs can be used in parallel, forming hybrid computer cluster configurations to achieve an even higher processing throughput. This paper evaluates the speedup of the parallel implementation of the Aho-Corasick and Wu-Manber algorithms on a hybrid GPU cluster, when used to process a snapshot of the Expressed Sequence Tags of the human genome and for different problem parameters.
