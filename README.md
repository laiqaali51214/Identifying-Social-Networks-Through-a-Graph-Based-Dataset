
# 🕸️ Project: Identifying Social Networks Through a Graph-Based Dataset

## 🚀 Overview  
This project explores **ego networks** using graph-based datasets to model social connections. Combining graph theory 📈, matrix algebra 🧮, and network visualization 🎨, we analyze social structures through node relationships and spectral graph properties.

---

## 🎯 Key Objectives  
- 🗃️ **Dataset Exploration**: Load and preprocess social network data  
- 🧩 **Graph Construction**: Build weighted graphs using Gaussian kernel similarity  
- 🔢 **Matrix Analysis**: Compute adjacency/Laplacian matrices  
- 📊 **Network Insights**: Identify clusters and connectivity patterns  
- 🖼️ **Interactive Visualization**: Create dynamic network visualizations  

---

## ✨ Features  
- 📂 **Data Pipeline**: `load_edges_from_file()` | `load_node_features()`  
- ⚖️ **Weighted Edges**: Gaussian kernel similarity for relationship strength  
- 🔗 **Matrix Operations**:  
  ```python
  adjacency_matrix = generate_weighted_adjacency_matrix(...)
  laplacian = generate_laplacian_matrix(...)
  ```
- 🌐 **Interactive Plots**: Spring layouts | Node coloring | Edge weighting  
- 🔍 **Spectral Analysis**: Eigenvalue sorting for community detection  

---

## 🔧 Installation  
1. **Dependencies**:  
   ```bash
   pip install networkx numpy pandas matplotlib scipy
   ```
2. **Dataset Setup**:  
   ```bash
   mkdir dataset
   # Add 0.edges and 0.feat files
   ```

---


## 🔎 Dataset Details  
| Metric          | Value       |
|-----------------|-------------|
| 📌 Total Nodes  | 347         |
| 🔗 Features/Node| 224         |
| ⚖️ Edge Type   | Undirected  |
| 🌟 Central Node | Node 0      |


---

## 📜 License  
MIT License - See [LICENSE](LICENSE) for details. ⚖️

---
