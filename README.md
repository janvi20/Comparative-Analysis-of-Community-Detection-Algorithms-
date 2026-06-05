# Community Detection in Complex Networks

A network science research project that evaluates and compares five state-of-the-art community detection algorithms on real-world and scale-free networks.

## Project Overview

Community detection is a fundamental task in graph analytics that identifies groups of highly connected nodes within a network. These communities reveal hidden structures that are valuable for applications such as:

- Social network analysis
- Recommendation systems
- Information diffusion
- Biological network analysis
- Viral marketing

This project compares the effectiveness of multiple community detection algorithms using both real-world datasets and artificially generated Barabási–Albert (BA) scale-free networks.

## Key Features

- Evaluated 5 community detection algorithms using Python and `igraph`
- Analyzed both real-world and synthetic networks
- Compared algorithm performance using multiple graph metrics
- Investigated community formation as networks evolve
- Measured computational efficiency and scalability

## Algorithms Evaluated

- Fast Greedy Modularity Optimization
- Label Propagation
- Infomap
- Multi-Level Modularity Optimization (Louvain)
- Walktrap

## Datasets

### Real-World Networks
- Netscience Collaboration Network
- Facebook TV Pages Network

### Synthetic Networks
- Barabási–Albert (BA) Scale-Free Networks
- Generated with varying growth parameters

## Evaluation Metrics

The algorithms were assessed using:

| Metric | Purpose |
|----------|----------|
| Modularity | Measures community quality |
| Conductance | Measures community separation |
| Coverage | Measures node assignment effectiveness |
| Execution Time | Measures computational efficiency |

## Results

### Key Findings

- Multi-Level (Louvain) consistently achieved the highest modularity scores.
- Fast Greedy and Walktrap delivered strong overall performance.
- Infomap produced meaningful communities but required longer execution times.
- Network topology significantly influenced algorithm effectiveness.
- Community structures became more distinct as scale-free networks evolved.

## Tech Stack

- Python
- igraph
- NetworkX
- NumPy
- Matplotlib
- Graph Theory
- Network Science

## Skills Demonstrated

- Graph Analytics
- Network Science
- Algorithm Evaluation
- Data Analysis
- Performance Benchmarking
- Research Methodology
- Scientific Computing

## Future Improvements

- Support for weighted and directed networks
- Dynamic community detection in temporal graphs
- Analysis of overlapping communities
- Large-scale network benchmarking

## Author

**Janvi Patel**

Graduate Research Project | Network Science & Graph Analytics
