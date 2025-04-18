# 📊 Fiedler's Theory of Spectral Graph Partitioning

This repository presents a detailed exploration of **Fiedler’s Theory of Spectral Graph Partitioning** — a powerful technique in graph theory and network analysis for dividing a graph into meaningful, balanced, and connected partitions using the **second smallest eigenvalue** and its associated **Fiedler vector**.

## 📖 Overview

**Spectral Graph Partitioning** uses the properties of a graph's **Laplacian matrix** to partition nodes into two or more connected components.  
This project focuses on:
- The theoretical foundations proposed by **Miroslav Fiedler**.
- Mathematical proof of correctness.
- Python implementations of spectral partitioning on example graphs.
- Discussion of real-world applications, limitations, and possible future extensions.


## 📚 Theory Highlights

- Constructs the **graph Laplacian matrix** using adjacency and degree matrices.
- Uses the **second smallest eigenvalue (λ₂)**, known as the **Fiedler value**, and its corresponding **Fiedler vector**.
- Partitions the graph by the **signs of the entries** in the Fiedler vector.
- Minimizes the number of edges cut between partitions while encouraging balance.
- Proves that the resulting subgraphs are **always connected**.


## 📝 Project Content

| 📄 File                  | 📑 Description                                           |
|:-------------------------|:--------------------------------------------------------|
| `presentation.pdf`        | Complete presentation slides explaining theory, proof, and examples |
| `spectral_partitioning.py`| Python implementation of spectral graph partitioning    |
| `README.md`               | Project documentation and overview                      |

## ⚙️ Implementation Examples

Two example graphs are partitioned using the Fiedler vector:
- **Example 1**: 8-node graph with 2 lost edges post partition.
- **Example 2**: 10-node graph with 2 lost edges post partition.

Both examples demonstrate the effectiveness of spectral partitioning in minimizing cut edges and balancing subgraphs.


## ⚠️ Limitations

The technique may not work effectively on:
- **Star graphs** or graphs with highly skewed degree distributions.
- Graphs with **uneven edge densities**.
- In such cases, the partition produced by the Fiedler vector may be unbalanced or less meaningful.


This project demonstrates both the **theoretical depth** and **practical applications** of **Fiedler’s Spectral Graph Partitioning** through detailed mathematical proofs, Python implementations, and case studies.


## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

For questions or collaborations, feel free to connect:
