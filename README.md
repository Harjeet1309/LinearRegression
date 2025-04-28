# Linear Regression - Housing Price Prediction

## 📚 Project Overview

This project implements both **Simple Linear Regression** and **Multiple Linear Regression** on the **Housing Price Prediction** dataset.  
It was developed as part to understand regression modeling, evaluation metrics, and model interpretation.

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

- **Source**: [Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- **Attributes**: area, bedrooms, bathrooms, stories, parking, furnishing status, etc.
- **Target Variable**: `price`

---

## 🧩 Project Workflow

### 1. Data Preprocessing
- Loaded the dataset.
- Handled categorical variables using one-hot encoding (`get_dummies`).

### 2. Simple Linear Regression
- **Input Feature**: `area`
- **Target Variable**: `price`
- **Steps**:
  - Train-test split.
  - Trained Linear Regression model.
  - Evaluated model with MAE, MSE, and R² Score.
  - Plotted **Regression Line** (Area vs Price).

### 3. Multiple Linear Regression
- **Input Features**: All available features (after encoding).
- **Target Variable**: `price`
- **Steps**:
  - Train-test split.
  - Trained Multiple Linear Regression model.
  - Evaluated model with MAE, MSE, and R² Score.
  - Plotted:
    - Actual vs Predicted Prices
    - Residual Plot
    - Feature Importance (Bar Plot)

---

## 📊 Visualizations

| Plot | Description |
|:-----|:------------|
| **Simple Regression Line** | Relationship between Area and Price. |
| **Actual vs Predicted Scatter** | How closely predictions match actual prices. |
| **Residuals Plot** | Distribution of prediction errors (ideal randomness). |
| **Feature Importance Bar Plot** | Influence of each feature on price prediction. |

---

## 📈 Evaluation Metrics

| Metric | Description |
|:-------|:------------|
| **MAE (Mean Absolute Error)** | Average absolute difference between predicted and actual prices. |
| **MSE (Mean Squared Error)** | Average of the squared differences. |
| **R² Score** | How well the features explain the variation in price (closer to 1 is better). |

---
