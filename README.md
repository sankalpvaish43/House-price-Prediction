# 🏠 House Price Prediction using Machine Learning

## Overview

This project predicts house prices using multiple machine learning regression algorithms. It includes data preprocessing, feature engineering, model comparison, and evaluation to identify the best-performing model.

The project was implemented in Python using the Scikit-learn library.

---

## Features

- Data preprocessing and cleaning
- Missing value handling
- Feature engineering
- One-hot encoding of categorical features
- Feature scaling
- Comparison of multiple regression algorithms
- Hyperparameter tuning
- Feature importance analysis
- House price prediction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/shree1992/housedata/data

After downloading, place `data.csv` in the project folder before running the notebook.

---

## Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor
- K-Nearest Neighbors
- Support Vector Regressor (SVR)

---

## Best Model Performance

**Gradient Boosting Regressor**

- R² Score: **0.6686**
- Mean Absolute Error (MAE): **102,710.95**
- Root Mean Squared Error (RMSE): **202,920.32**

---

## Feature Engineering

Additional features created include:

- House Age
- Sale Year
- Sale Month
- Renovation Status
- ZIP Code Extraction

---

## How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Download the dataset from Kaggle.
4. Place `data.csv` in the project folder.
5. Open and run the Jupyter Notebook.

---

## Project Structure

```
House-Price-Prediction/
│── House_Price_Prediction.ipynb
│── README.md
│── requirements.txt
```

---

## Author

**Sankalp Vaish**
