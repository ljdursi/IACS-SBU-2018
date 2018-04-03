# Dispatches from the Convergence Coalface: HPC, Big Data, and Large Scale Genomics

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

This is the presentation and associated materials for [my talk](https://www.iacs.stonybrook.edu/event/seminars/dispatches-from-the-convergence-coalface-hpc-big-data-and-large-scale-genomics)
at [The Institute for Advanced Computational Science](https://www.iacs.stonybrook.edu)
at [Stony Brook](http://www.stonybrook.edu).

Slides can be viewed directly at https://ljdursi.github.io/IACS-SBU-2018/ .

## Abstract

As we compute at ever-larger scale, and the problems we can model
get richer and more complex, there is increasing discussion about
potential convergence of HPC, with its traditional science simulation
focus, and Big Data, with its history in analytics and predictive
modelling.  With one foot outside of each community, genomic
bioinformatics tool builders have been quietly chipping away at the
walls between the two, building on the one hand high-performance
multithreaded C++ tools with emphasis on cache reuse and (increasingly)
numerical methods that would be familiar to those working the HPC
tunnels, and on the other hand database-inspired distributed systems
with complex cloud workflow orchestration that those mining the big
data seams would immediately recognize.

In this talk, we discuss several current projects in large scale
genomics, from the perspective of someone new to the field but
experienced in large scale scientific computation, that illustrate
the increasing need for convergence - large-scale cancer whole-genome
genomics (the ICGC/TCGA PCAWG project), high-throughput nanopore
sequencing, and CanDIG (http://www.distributedgenomics.ca), a
distributed, federated platform for national-scale genomics analyses.
We discuss open algorithm, tooling, and “data-plumbing” issues in
these areas, where the field could learn more from HPC, and where
the HPC and Big Data communities could learn from the work going
on in genomics.
