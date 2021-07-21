# An HPC oversubscription model

# Overview
This is an oversubscription model for HPC systems. The model contains job
scheduling and resource allocation framework to safely oversubscribe an HPC
system. A supply-function bidding mechanism is used to enable user
participation in the scheme. We use logarithmic fitting model for various power
and performance values based on the power-capping levels.

# Data
Power and performance data collected and used from the literature (e.g., Patel
et al. "PERQ: Fair and Efficient Power Management of Power-Constraint
Large-Scale Computing Systems", HPDC'19).

Job trace collected from the parallel workload archive
(https://www.cs.huji.ac.il/labs/parallel/workload/).

# Simulation tests
Some example test files inside the "simulation_tests" folder.
