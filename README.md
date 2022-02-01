# Parkinsons-Predictor
Model which predicts whether a person suffers from Parkinsons or not based on some features.

Dataset was taken from [**Parkinsons Dataset**](https://archive.ics.uci.edu/ml/datasets/parkinsons).

Algorithm used for the prediction is [**XGBoost**](https://xgboost.readthedocs.io/en/stable/).

An accuracy of `94.871%` was acheived without much Data Processing.

But an accuracy of `98.305%` was acheived after Over Sampling our data using [**imbalanced-learn**](https://imbalanced-learn.org/stable/) library.
