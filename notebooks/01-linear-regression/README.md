# Linear regression

Introduction to supervised regression using scikit-learn's `LinearRegression`, applied to three datasets with increasing complexity.

## Topics covered

- Fitting a linear regression model with scikit-learn
- Train/test split with `train_test_split`
- Univariate and multivariate regression
- Model evaluation (R² score)

## Problems

| # | Problem | Description |
|---|---------|-------------|
| 1 | Revenue vs. share price | Univariate regression: predict share price from company revenue; train on first 100 samples, test on the rest |
| 2 | Iris petal length vs. width | Univariate regression on the Iris dataset; visualise the fitted line over the scatter plot |
| 3 | Car MPG | Multivariate regression using multiple vehicle attributes to predict fuel efficiency |

## Datasets

| File | Description |
|------|-------------|
| `revenue-share-price.csv` | Company revenue and share price pairs |
| `iris.csv` | Iris flower measurements (sepal/petal length and width, species label) |
| `car_mpg.csv` | Vehicle attributes and fuel efficiency (miles per gallon) |

## Files

| File | Description |
|------|-------------|
| `linear-regression.ipynb` | Main practice notebook |
| `Iris3ClassClassifier.JPG` | Illustration of the Iris three-class problem |
