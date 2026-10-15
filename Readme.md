# Deep Learning with Normalization and Regularization

Keras neural networks that classify the scikit-learn Breast Cancer Wisconsin dataset (569 samples, 30 features). The notebook compares a baseline model against batch normalization and against L2 regularization with dropout.

## Workflow

1. Load the data and split it into train, validation and test sets
2. Standardize features, fitting the scaler on the training set only
3. Train a baseline model (Dense 32 -> 16 -> 1)
4. Add batch normalization
5. Add L2 regularization (1e-4) and dropout (0.3)
6. Evaluate on the test set and plot accuracy over epochs

All models use Adam, binary cross-entropy, 50 epochs and a batch size of 32.

## Contents
- 'CG_C10_M01.ipynb' Notebook file on Breast cancer
- 'CG_C10_M01.ipynb' Notebook file on California Housing.