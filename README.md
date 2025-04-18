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
- Computes the **second smallest eigenvalue (λ₂)** — the **Fiedler value**.
- Uses the **Fiedler vector** (the eigenvector corresponding to λ₂) to partition the graph based on the signs of its entries.
- Aims to:
  - Minimize the number of edges cut between partitions.
  - Maintain balance in the size of partitions.
- Guarantees that resulting subgraphs remain **connected** under typical conditions.



## 📝 Project Content

| 📄 File                  | 📑 Description                                           |
|:-------------------------|:--------------------------------------------------------|
| `presentation.pdf`        | Complete presentation slides explaining theory, proof, and examples |
| `spectral_partitioning.py`| Python implementation of spectral graph partitioning    |
| `README.md`               | Project documentation and overview                      |

This project demonstrates both the **theoretical depth** and **practical applications** of **Fiedler’s Spectral Graph Partitioning** through detailed mathematical proofs, Python implementations, and case studies.


## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

For questions or collaborations, feel free to connect:
