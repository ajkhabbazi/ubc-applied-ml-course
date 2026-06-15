# Linear two-class classification

Binary classification using logistic regression, applied to tabular and image data.

## Topics covered

- Logistic regression with scikit-learn's `LogisticRegression`
- Decision boundary visualisation
- Binary classification on image data (MNIST subset)
- Effect of adding features on classifier performance

## Problems

| # | Problem | Description |
|---|---------|-------------|
| 1 | Cat-Dog (nose size) | Univariate logistic regression: predict cat or dog from nose size; 33% test split |
| 2 | Cat-Dog (nose + ear) | Extend to two features (nose size and ear shape); compare decision boundaries |
| 3 | MNIST 0-vs-1 digit classifier | Train a binary classifier to distinguish handwritten 0s from 1s using 28×28 pixel images |

## Datasets

| File | Description |
|------|-------------|
| `cat-dog.csv` | Nose size and ear shape measurements with cat/dog labels |
| MNIST images | Handwritten digit images (folders: `training/`, `testing/`) |

## Files

| File | Description |
|------|-------------|
| `two-class-classification.ipynb` | Main practice notebook |
| `MNIST.JPG`, `MNIST2.jpg` | MNIST dataset illustrations |
