# Feature engineering and learning

Nonlinear feature engineering with polynomial transforms, cross-validation for model selection, and the bias-variance trade-off.

## Topics covered

- Polynomial feature engineering with `sklearn.preprocessing.PolynomialFeatures`
- Manual quadratic feature transforms
- k-fold cross-validation with `cross_val_score`
- Bias-variance trade-off and model complexity selection
- R² evaluation for regression

## Problems

| # | Problem | Description |
|---|---------|-------------|
| 1 | Free-fall distance vs. time | Engineer quadratic features (d = ½gt²) and fit a polynomial regressor; compare manual transform against `PolynomialFeatures`; evaluate with R² |
| 2 | Iris nonlinear classification | Apply `PolynomialFeatures` to sepal length/width to generate a nonlinear decision boundary for the Iris 3-class problem |
| 3 | Cross-validation | Apply k-fold cross-validation to select the polynomial degree that minimises validation error; examine the bias-variance trade-off across model complexities |

## Datasets

| File | Description |
|------|-------------|
| `gravity_data.csv` | Distance vs. time measurements from free-fall |
| `iris.csv` | Iris flower measurements (sepal/petal length and width, species label) |
| `quad.csv` | Dataset for polynomial regression exercises |

## Files

| File | Description |
|------|-------------|
| `feature-engineering-learning.ipynb` | Main practice notebook |
| `Validation.PNG` | Illustration of train/validation/test split strategy |
| `Iris3ClassClassifier.JPG` | Iris three-class problem schematic |
