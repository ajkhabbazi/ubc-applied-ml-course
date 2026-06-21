# UBC applied machine learning

**Course notebooks and projects from Applied Machine Learning — University of British Columbia**

*Applied Machine Learning — University of British Columbia*

Arash J. Khabbazi

[![Language](https://img.shields.io/badge/language-Python-blue)](https://www.python.org/)
[![Notebooks](https://img.shields.io/badge/format-Jupyter-orange)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

> **TL;DR** Jupyter notebooks and course projects covering the core supervised and unsupervised machine learning methods taught in UBC's Applied Machine Learning course — from linear regression and logistic classification to neural networks, dimensionality reduction, and clustering. Includes two image classification projects on Lego sorting.

---

## Overview

Practice notebooks and course projects from the Applied Machine Learning course at the University of British Columbia. The course covers the mathematical foundations and practical implementation of classical machine learning methods using Python and scikit-learn, progressing from linear models through neural networks and unsupervised learning.

Each notebook in `notebooks/` corresponds to a lecture module and includes worked examples, visualizations, and exercises on real datasets. The `projects/` directory contains two-stage image classification projects.

---

## Contents

### Notebooks

| Folder | Topic | Key concepts |
|--------|-------|--------------|
| `01-linear-regression/` | Linear regression | Least squares, regularization, multivariate regression |
| `02-two-class-classification/` | Linear two-class classification | Logistic regression, decision boundary, gradient descent |
| `03-multi-class-classification/` | Linear multi-class classification | One-vs-all, softmax, multi-class logistic regression |
| `04-dimensionality-reduction/` | Dimensionality reduction | PCA, SVD, collaborative filtering |
| `05-feature-engineering-selection/` | Feature engineering and selection | Polynomial features, filter/wrapper methods, mutual information |
| `06-feature-engineering-learning/` | Feature engineering and learning | Cross-validation, model selection, bias–variance trade-off |
| `07-neural-networks/` | Neural networks | Feedforward networks, backpropagation, activation functions |
| `08-clustering/` | Clustering | K-means, hierarchical clustering, silhouette analysis |

### Projects

| Folder | Project | Description |
|--------|---------|-------------|
| `projects/01-lego-sorting-raw-images/` | Lego sorting — stage 1 | Single-neuron classifier on raw RGB images; Lego pieces classified into rectangles, squares, and circles |
| `projects/02-lego-sorting-engineered-features/` | Lego sorting — stage 2 | 3-class logistic regression on engineered features (≤64 per image); handles off-centre and rotated pieces |

---

## How to use

**Requirements:** Python 3.x, Jupyter, NumPy, Pandas, scikit-learn, Matplotlib.

```bash
pip install numpy pandas scikit-learn matplotlib jupyter
jupyter notebook
```

Open any `.ipynb` file in the `notebooks/` or `projects/` directory and run cells sequentially. Datasets are included in each subfolder.

---

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT).

---

## Contact

**Arash J. Khabbazi** — School of Mechanical Engineering, Purdue University  
[arashjkh@gmail.com](mailto:arashjkh@gmail.com)
