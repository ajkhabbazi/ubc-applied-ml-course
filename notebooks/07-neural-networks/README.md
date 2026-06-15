# Neural networks

Multi-layer perceptron classifiers with scikit-learn, applied to image classification on MNIST digits.

## Topics covered

- `MLPClassifier` from `sklearn.neural_network`
- Configuring hidden layer depth and width (`hidden_layer_sizes`)
- Counting trainable parameters
- Effect of architecture on accuracy and training time

## Problems

| # | Problem | Description |
|---|---------|-------------|
| 1 | Architecture comparison | Train and compare two MLP configurations: (a) 1 hidden layer, 10 neurons; (b) 2 hidden layers, 7 neurons each. Calculate parameter counts for each. |
| 2 | MNIST digits classifier | Train a 10-class MLP on 8×8 scaled MNIST digit images; evaluate accuracy on the held-out test set; compare against logistic regression baseline from earlier notebooks |

## Files

| File | Description |
|------|-------------|
| `neural-networks.ipynb` | Main practice notebook |
| `DigitsClassifier.JPG` | Illustration of the MNIST digits classification task |
