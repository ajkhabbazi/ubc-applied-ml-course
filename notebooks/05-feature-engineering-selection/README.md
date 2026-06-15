# Feature engineering and selection

Selecting informative features from high-dimensional data and engineering features from raw inputs (images) to enable effective classification.

## Topics covered

- Filter and wrapper feature selection methods
- Mutual information for feature ranking
- Manual feature engineering from image data
- Reducing sensor requirements through feature selection

## Problems

| # | Problem | Description |
|---|---------|-------------|
| 1 | Spectrometer feature selection | Select the 2 most informative features (out of 8 spectrometer channels) to train a classifier; goal is to reduce hardware cost by using fewer sensors |
| 2 | UAV landing-assist | Engineer features from camera images to classify ground terrain as flat or rough; train a `LogisticRegression` model on the engineered features |

## Datasets

| File | Description |
|------|-------------|
| `spectrometer_dataset_2.csv` | Spectrometer readings across 8 frequency channels with class labels |

## Files

| File | Description |
|------|-------------|
| `feature-engineering-selection.ipynb` | Main practice notebook |
| `notes.ipynb` | Supplementary notes on feature selection methods |
| `Lecture 7 Feature Engineering and Selection - Practice.jpg` | Lecture slide reference |
