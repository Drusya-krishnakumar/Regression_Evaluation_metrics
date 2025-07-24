# 🏡 California Housing Price Prediction - Regression Models

This project evaluates multiple regression algorithms on the California Housing dataset to predict median house prices based on features such as income, location, number of rooms, etc.

---

## 📌 Objective

- Apply multiple supervised regression algorithms
- Perform preprocessing, EDA, and feature scaling
- Evaluate models using standard metrics
- Use 5-fold cross-validation and GridSearchCV for tuning
- Select the best-performing model

---

## 📂 Dataset

- Source: `sklearn.datasets.fetch_california_housing`
- Features: 8 numerical predictors
- Target: `MedHouseVal` (Median house value)

---

## ⚙️ Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)

---

## 📈 Evaluation Metrics

Each model was evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### ✅ Final Results:

| Model              | MAE    | MSE    | R² Score |
|-------------------|--------|--------|----------|
| Linear Regression | 0.3920 | 0.2711 | 0.6859   |
| Decision Tree     | 0.4033 | 0.3599 | 0.5830   |
| **Random Forest** | **0.2788** | **0.1661** | **0.8075** |
| Gradient Boosting | 0.3079 | 0.1838 | 0.7871   |
| SVR               | 0.3162 | 0.1996 | 0.7687   |

---

## 🔍 Hyperparameter Tuning

**Random Forest Best Params:**
{'max_depth': 20, 'n_estimators': 100}

## 🏆 Best Model
Random Forest Regressor was selected due to:

* ighest R² score on test data

* Robust performance after tuning

* Handles non-linear features and outliers well

### 📝 How to Run
Clone the repository

Open the Jupyter Notebook (california_regression_analysis.ipynb)

Run all cells to load data, preprocess, train, evaluate, and tune models

### 📚 Libraries Used
pandas

numpy

matplotlib / seaborn

scikit-learn

#### 
📧 Contact <br>
Developed by :Drusya Krishnakumar
For academic purposes — supervised learning assignment
