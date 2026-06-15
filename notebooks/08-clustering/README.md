# Clustering

Unsupervised learning with K-means clustering, applied to wheat seed classification without labels.

## Topics covered

- K-means clustering with `sklearn.cluster.KMeans`
- Inertia (total within-cluster squared distance) and the elbow method
- Cluster centroid interpretation
- Evaluating cluster quality without ground-truth labels

## Problems

| # | Problem | Description |
|---|---------|-------------|
| 1 | Wheat seeds | Cluster seeds by physical measurements (length, width, area, perimeter, asymmetry, compactness, groove length); determine the number of seed types without using the species labels; compare discovered clusters to the three known wheat varieties (Kama, Rosa, Canadian) |

## Dataset

| File | Source | Description |
|------|--------|-------------|
| `seeds.csv` | [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/seeds) | 210 wheat seed samples with 7 geometric measurements and species label |

## Files

| File | Description |
|------|-------------|
| `clustering.ipynb` | Main practice notebook |
