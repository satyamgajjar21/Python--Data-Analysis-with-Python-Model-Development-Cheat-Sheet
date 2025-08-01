# 📊 Data Analysis with Python – Model Development Cheat Sheet

This repository contains a quick-reference cheat sheet for **model development using Python**, particularly focusing on **Linear Regression**, **Polynomial Regression**, and **Pipeline-based modeling** using `scikit-learn`, `numpy`, and `seaborn`.

---

## 🚀 Getting Started

This cheat sheet is ideal for learners or professionals who want to:
- Quickly recall model development steps.
- Use practical code snippets for linear and polynomial regression.
- Understand model evaluation metrics like **R²** and **MSE**.

---

## 🧠 Concepts & Code Examples

### 🔹 Linear Regression

```python
from sklearn.linear_model import LinearRegression

# Create model
lr = LinearRegression()

# Train the model
X = df[['attribute_1', 'attribute_2']]
Y = df['target_attribute']
lr.fit(X, Y)

# Predict
Y_hat = lr.predict(X)

# Coefficients
coeff = lr.coef_
intercept = lr.intercept_


