# Fair Cake Cutting with Network Structures

## Overview

This repository explores an alternative approach to the classical notion of fairness in cake cutting. Instead of traditional methods, we introduce an underlying network structure among agents and investigate local fairness within this graphical setting. The focus is on efficient moving-knife algorithms, both discrete and continuous, to achieve envy-free allocations on various network structures, primarily those resembling trees.

## Algorithms

### 1. Tree Networks

We start by modifying an existing algorithm designed for envy-free allocations on trees. The adaptation incorporates an additional edge at level 1 in the network while ensuring fairness.

### 2. Cycle Networks (up to 𝐶 6 )

We propose moving-knife algorithms for obtaining envy-free allocations on cycle networks, up to a specified limit (𝐶 6 ).

### 3. Cliques Connected via a Bridge

We present moving-knife algorithms tailored for envy-free allocations on networks consisting of cliques connected by a bridge.


## Conclusion

In this report, we've explored and explored moving-knife algorithms for envy-free cake-cutting on diverse network structures. The focus on continuous methods, particularly moving knives, simplifies the process and often requires fewer cuts than their discrete counterparts.

## Future Work

We briefly discuss potential extensions to our results and welcome contributions and enhancements to the existing algorithms.
