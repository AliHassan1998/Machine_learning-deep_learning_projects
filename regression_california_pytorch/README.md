# 🏡 California Housing Price Prediction with PyTorch

This project demonstrates a regression model built with PyTorch to predict California housing prices using the built-in `fetch_california_housing` dataset from `sklearn`.

## 📦 Dataset
- `fetch_california_housing` from `sklearn.datasets`
- 8 input features

## 🧠 Model Architecture
- Multi-layer neural network with:
  - 64 → 128 → 10 → 1 neurons
  - `ReLU` activations
  - `MSELoss` for loss function
  - `SGD` optimizer

## 🧪 Evaluation
- `Mean Squared Error` used on test set
- Model is saved and loaded using `torch.save()` and `torch.load()`

## 🧰 Tools Used
- PyTorch
- Sklearn
- Google Colab / Python

## 📁 Files
- `regression_california_pytorch.py` — Full code in Python
- `Regression_with_Pytorch_for_California_Housing_Price_Prediction.ipynb` — Notebook version (optional)

