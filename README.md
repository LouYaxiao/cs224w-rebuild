CS224W Rebuild — Learning Graph Machine Learning by Reconstruction

This repository contains my lecture-by-lecture rebuild of  
Stanford CS224W: Machine Learning with Graphs.

Instead of copying assignments, I reconstruct core ideas through:

- Minimal runnable experiments
- Clean conceptual notes
- Structural understanding of graph learning

Philosophy

Graph learning is not just about APIs.

This rebuild focuses on:

- Structural reasoning (random walk, matrix view, invariance)
- Minimal experiments over small graphs
- Understanding the transition:
  
  Traditional Graph ML → Node Embeddings → GNNs

Progress

- [x] L01 — Graph basics and core tasks  
- [x] L02 — Traditional graph ML (Random Walk, Centrality, PageRank)  
- [ ] L03 — Node embeddings (DeepWalk / co-occurrence intuition)  
- [ ] GNN foundations  
- [ ] Expressiveness and WL test
      
Notes

- [L01 — Graph Basics](notes/L01.md)
- [L02 — Traditional Graph ML](notes/L02.md)

Notebooks

All experiments are minimal and runnable.

L01
- `notebooks/L01_graph_basics.ipynb`
  - Construct graphs with NetworkX
  - Degree, connected components
  - Basic structural inspection

L02
- `notebooks/L02_traditional_graph_ml.ipynb`
  - Random walk simulation
  - Centrality comparison
  - PageRank vs empirical visit frequency

How to Run

```bash
conda env create -f environment.yml
conda activate se-graph
jupyter notebook

