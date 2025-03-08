# flowshop_permutation_problem

# Graph-Based Imitation Learning for Permutation Flow Shop Scheduling (PFSS)

## 📌 Project Overview
This repository implements a **Graph-Based Imitation Learning (GraphIL) model** to solve the **Permutation Flow Shop Scheduling (PFSS)** problem.  
The model learns from **expert solutions (NEH heuristic)** and uses a **Graph Neural Network (GNN) with attention mechanisms**  
to predict optimal job sequences that minimize the **makespan**.

## 🚀 Features
- Implements **Graph-Based Imitation Learning (IL)** using **Gated Graph Convolutional Networks (GGCN)**.
- Learns scheduling from **expert solutions (NEH heuristic)**.
- Trains using **supervised learning** and optimizes using **CrossEntropyLoss**.
- Supports **variable job and machine configurations**.
- Provides **evaluation results** with predicted sequences and makespan.
