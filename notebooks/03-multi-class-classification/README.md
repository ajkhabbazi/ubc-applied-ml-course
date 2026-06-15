# Linear multi-class classification

Extending binary logistic regression to multi-class problems using one-vs-rest and softmax strategies.

## Topics covered

- Multi-class logistic regression (one-vs-rest)
- Confusion matrix and accuracy evaluation
- Decision boundary visualisation in feature space
- Scaling to high-dimensional image inputs

## Problems

| # | Problem | Description |
|---|---------|-------------|
| 1 | Iris 3-class (2 features) | Classify Iris species using sepal length and sepal width; plot decision boundary and confusion matrix; 33% test split |
| 2 | Iris 3-class (4 features) | Extend to all four Iris features; compare accuracy improvement over 2-feature model |
| 3 | MNIST digits classifier (0–9) | Train a 10-class classifier on 8×8 scaled MNIST digit images; evaluate on held-out test set |

## Datasets

| File | Description |
|------|-------------|
| `iris.csv` | Iris flower measurements (sepal/petal length and width, species label) |
| MNIST images | Handwritten digit images (folders: `training/`, `testing/`) |

## Files

| File | Description |
|------|-------------|
| `multi-class-classification.ipynb` | Main practice notebook |
| `DigitsClassifier.JPG` | Illustration of the MNIST digits problem |
| `Iris3ClassClassifier.JPG` | Illustration of the Iris three-class problem |
