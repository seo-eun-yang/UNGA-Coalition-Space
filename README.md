# UNGA Coalition Space

**Interactive visualization accompanying the research project:**

**From Preference Space to Coalition Space: Measuring Dynamic Multilateral Relationships with Hypergraph Embeddings**

Sunny Yang  
Northeastern University

## Overview

How should relationships among states be measured in a political world organized
through multilateral institutions and collective action?

This project distinguishes between **preference space** and **coalition space** in
international politics.

Traditional measures based on United Nations General Assembly (UNGA) roll-call
votes, including ideal-point and item-response-theory (IRT) models, estimate where
states stand on latent preference dimensions. These measures provide powerful
representations of political preferences, but they do not directly capture the
multilateral coalitions through which states collectively advance political
initiatives.

This project instead uses **UNGA resolution co-sponsorship** to recover a dynamic
coalition space. Each resolution is represented as a hyperedge connecting its
co-sponsoring states, and a temporal hypergraph model learns multidimensional
country representations from these repeated patterns of collective political
association.

In short:

> **Preference space:** Where does a state stand?  
> **Coalition space:** With whom, and within which multilateral configurations,
> does a state act?

## Interactive Coalition Space

The interactive visualization presents the evolving geometry of UNGA coalition
relationships over time.

The visualization can be used to explore:

- country positions and trajectories;
- coalition neighborhoods and clusters;
- changes in multilateral alignment over time;
- relationships among historically recognized political groups; and
- similarities and differences between states within the learned coalition space.

The displayed 3D coordinates are dimensionality-reduced representations of the
underlying embeddings and are intended for visualization. Substantive similarity
and validation analyses are conducted in the original high-dimensional embedding
space.

## Method

UNGA resolution co-sponsorship is represented as a temporal hypergraph in which
states are nodes and each resolution's set of co-sponsors constitutes a hyperedge.

The model learns dynamic country embeddings from repeated multilateral
co-sponsorship events. The resulting relational geometry allows the analysis of
distances, neighborhoods, clusters, bridge positions, coalition boundaries, and
temporal trajectories.

The broader measurement question is whether this coalition-space representation
contains politically meaningful relational information beyond established
voting-based preference measures.

## Research Status

This repository presents an interactive output from an ongoing research project.
The manuscript and analyses are currently under development. Results and
visualizations may therefore be updated as the project progresses.

## Citation

Yang, Sunny. "From Preference Space to Coalition Space: Measuring Dynamic
Multilateral Relationships with Hypergraph Embeddings." Working paper.

## Author

**Sunny Yang**  
Northeastern University
