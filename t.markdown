<!-- ---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<!-- # Enumeration of Maximal Cliques

The following 3 algorithms were implemented to enumerate the maximal cliques in a graph:

- [Bron Kerbosch Algorithm](/bka)
- [Chiba](/chiba)
- [Tomita](/tomita) -->

# Design and Analysis of Algorithms - Assignment 1

## Problem Statement:

The goal of the assignment is implement maximal clique enumeration algorithm from three given papers.

1. The worst-case time complexity for generating all maximal cliques and computational experiments. \[[Bron-Kerbosch Algorithm](/bka)\]

2. Listing All Maximal Cliques in Sparse Graphs in Near-Optimal Time. \[[CLIQUE Algorithm](/tomita)\]

3. Arboricity and Subgraph Listing Algorithms. \[[Chiba Arboricity Algorithm](/chiba)\]

A clique is a collection of vertices wherein every pair of vertices is connected to each other. In other words, a clique is a subset of an undirected graph where each vertex is adjacent to each other. A maximal clique is a clique in which another vertex cannot be added while remaining to be a clique (i.e the largest number of vertices that can be added to maintain the property of each vertex being adjacent to each other).

### Applications of Cliques

- Social Network : Maximal cliques can be used to identify communities or groups in which all members are connected to each other. It can further be used for friend recommendation systems or user prefernce systems
- Biological Applications: Proteins can be represented as nodes and their interactions can be modelled in edges. In this case, finding maximal cliques indicate the presence of a functional protein complex
- Frequency Allocation in Wireless Communication: Wireless devices can be represented as nodes and an edge is marked between the nodes if the devices can interfere with each other. In this case, finding maximal cliques can identify groups of devices for which the same frequency should not be allocated.

### Datasets

The implementations for all the algorithms were tested using the following 3 datasets:

- [Email Enron Network](/email)
- [Autonomous Systems by Skitter](/skitter)
- [Wikipedia Vote Network](/wiki) -->
