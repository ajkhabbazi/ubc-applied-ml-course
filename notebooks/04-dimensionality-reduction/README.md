# Dimensionality reduction

Unsupervised dimensionality reduction with PCA and SVD, applied to spectrometry classification, image compression, and collaborative filtering.

## Topics covered

- Feature standardisation with `StandardScaler`
- Principal component analysis (PCA) with `sklearn.decomposition.PCA`
- Dimensionality reduction as a preprocessing step for classification
- SVD-based collaborative filtering for recommendation systems

## Problems

| # | Problem | Description |
|---|---------|-------------|
| 1 | Spectrometry | Reduce 8 spectrometer features to 2 with PCA; train and test a classifier on the reduced features; 33% test split |
| 2 | MNIST with PCA | Replace image rescaling with PCA (retain K = L² components); compare accuracy against L×L pixel-scaled images |
| 3 | Movie recommender | Apply PCA to a user–genre ratings matrix to extract K typical users; use the decomposition to recommend movie genres to a new user |

## Datasets

| File | Description |
|------|-------------|
| `spectrometer_dataset_2.csv` | Spectrometer readings across 8 frequency channels with class labels |
| `recom.csv` | User–movie genre rating matrix for collaborative filtering |

## Files

| File | Description |
|------|-------------|
| `dimensionality-reduction.ipynb` | Main practice notebook |
