# 📊 Fiedler's Theory of Spectral Graph Partitioning

This repository presents a detailed exploration of **Fiedler’s Theory of Spectral Graph Partitioning** — a powerful technique in graph theory and network analysis for dividing a graph into meaningful, balanced, and connected partitions using the **second smallest eigenvalue** and its associated **Fiedler vector**.

## 📖 Overview

**Spectral Graph Partitioning** leverages the spectral properties of a graph’s **Laplacian matrix** to efficiently partition its vertices.  
This project covers:
- The theoretical foundation as introduced by **Miroslav Fiedler**.
- A mathematical proof of correctness.
- Python implementation of spectral partitioning on example graphs.
- Real-world applications, limitations, and potential future extensions.


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
