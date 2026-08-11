# 🌀 Clustering

## 📌 Overview
Unsupervised learning module covering the three most common clustering algorithms — K-Means, Hierarchical, and DBSCAN — each applied to a dataset suited to showing its particular strengths (and failure cases).

## 📂 Files
| File | Description |
|---|---|
| `kmeans_clustering.ipynb` | K-Means clustering on synthetic blob data (`make_blobs`) |
| `hierarichal_clustering.ipynb` | Hierarchical (agglomerative) clustering on the Iris dataset |
| `DB_scane_clustering.ipynb` | DBSCAN clustering on synthetic moon-shaped data (`make_moons`), useful for showing density-based clustering on non-convex shapes |

## 🧠 Concepts Covered
- Centroid-based clustering (K-Means) & choosing K
- Agglomerative/hierarchical clustering & dendrograms
- Density-based clustering (DBSCAN) & the `eps`/`min_samples` parameters
- Feature scaling before clustering
- When each algorithm works well vs. when it fails (e.g. non-globular clusters for K-Means)

## ▶️ How to Run
Open any notebook in Jupyter and run all cells top to bottom. Start with `kmeans_clustering.ipynb` for the most intuitive introduction, then compare against `DB_scane_clustering.ipynb` to see why density-based clustering handles non-convex shapes better.
