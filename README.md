## 📊 Fiedler's Theory of Spectral Graph Partitioning

This repository offers an in-depth exploration of **Fiedler’s Theory of Spectral Graph Partitioning** — a foundational technique in graph theory and network analysis. It divides a graph into balanced, meaningful, and connected subgraphs using the properties of the **second smallest eigenvalue** (the **Fiedler value**) and its associated **Fiedler vector**.


## 📖 Overview
**Spectral Graph Partitioning** leverages the spectral properties of a graph’s **Laplacian matrix** to efficiently partition its vertices.

This project covers:
* 📘 The theoretical foundation as introduced by **Miroslav Fiedler**.
* ✅ A complete mathematical proof ensuring partition correctness and connectivity.
* 🧮 Python implementation of spectral partitioning on example graphs.
* 🌍 Real-world applications, key limitations, and directions for further exploration.

---

## 📚 Theory Highlights

* Constructs the **graph Laplacian matrix** from adjacency and degree matrices.
* Computes the **second smallest eigenvalue (λ₂)** — the **Fiedler value**.
* Uses the **Fiedler vector** (eigenvector of λ₂) to partition nodes based on the **signs of its entries**.
* The partitioning:
  * Minimizes the number of cut edges between groups.
  * Maintains a balanced size between the resulting partitions.
  * Ensures subgraphs remain **connected**, as proven mathematically.

## 🗂️ Project Contents

| 📄 File                    | 📑 Description                                                 |
| -------------------------- | -------------------------------------------------------------- |
| `presentation.pdf`         | Complete slide deck covering theory, proof, examples           |
| `main_paper.pdf`           | Final report paper documenting the research and implementation |
| `notebooks/`               | Jupyter notebooks for interactive demonstrations               |
| `latex_resources/`         | LaTeX source files used to generate the main paper             |

> 🔍 *Explore the notebooks, paper, and implementation files to understand, test, and extend the concepts presented.*


## 🤝 Let’s Connect!
😊 I’m always open to meaningful conversations, collaborative projects, and idea exchanges in the fields of graph theory, machine learning, and data science.
If you’re interested in discussing new insights, working together on related topics, or contributing to ongoing discussions — feel free to reach out!
Let’s learn and build together 🚀
