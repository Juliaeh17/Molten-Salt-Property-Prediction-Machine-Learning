# Molten Salt Property Prediction Using Machine Learning

This project applies machine learning to predict the melting point of molten salt compounds used in nuclear applications. The dataset includes experimental and theoretical information for salts such as UF₄, NaF, KF, and their binary/ternary mixtures.

## 📁 Files

- `Molten Salt Property Prediction_ML.ipynb`: The main Colab notebook containing data loading, preprocessing, model training, and evaluation.
- `requirements.txt`: List of packages used in the notebook.

## Features

- Loads a dataset of molten salt compositions and their properties.
- Performs feature engineering using:
  - Ionic radius
  - Electronegativity
  - Molecular weight
- Trains multiple regression models to predict melting point:
  - Linear Regression
  - Random Forest Regressor
- Evaluates models using metrics like MAE, RMSE, and R² score.

## Technologies Used

- Python
- Libraries:
  - pandas
  - numpy
  - torch
  - scikit-learn
  - matplotlib
  - xgboost

## Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/Juliaeh17/Molten-Salt-Property-Prediction-Machine-Learning.git
cd Molten-Salt-Property-Prediction-Machine-Learning
