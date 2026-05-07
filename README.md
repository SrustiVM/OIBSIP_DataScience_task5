# 📈 Advertising Sales Prediction using Regression Models

## 📌 Project Overview
This project predicts product sales based on advertising expenditure across different marketing platforms such as TV, Radio, and Newspaper.

The project applies multiple regression techniques including:
- Linear Regression
- Lasso Regression
- Ridge Regression

The workflow includes data preprocessing, multicollinearity analysis, model training, evaluation, visualization, and cross-validation.

---

## 🎯 Objective
- Analyze the relationship between advertising spending and sales
- Build predictive regression models
- Compare Linear, Lasso, and Ridge Regression
- Evaluate model performance using statistical metrics
- Understand feature importance and multicollinearity

---

## 📂 Dataset
Dataset Used: `Advertising.csv`

Features:
- TV Advertising Budget
- Radio Advertising Budget
- Newspaper Advertising Budget

Target Variable:
- Sales

---

## 🛠️ Libraries Used
- Pandas
- Matplotlib
- Scikit-learn
- Statsmodels

---

## ⚙️ Steps Performed

### 1. Load Dataset
Loaded advertising dataset using Pandas.

### 2. Basic Data Understanding
- Checked dataset shape
- Viewed dataset information
- Generated summary statistics
- Removed unnecessary columns

### 3. Feature & Target Split
Separated:
- Independent variables (X)
- Target variable (y)

### 4. Train-Test Split
Split dataset into training and testing sets using Scikit-learn.

### 5. Multicollinearity Check (VIF)
Calculated Variance Inflation Factor (VIF) to identify multicollinearity among features.

### 6. Model Training
Trained three regression models:
- Linear Regression
- Lasso Regression
- Ridge Regression

### 7. Predictions
Generated predictions using all trained models.

### 8. Model Evaluation
Evaluated models using:
- R² Score
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)

### 9. Coefficient Analysis
Compared feature coefficients across different regression models.

### 10. Visualization
Visualized Actual vs Predicted Sales using scatter plot.

### 11. Cross Validation
Applied 5-Fold Cross Validation to evaluate model generalization.

---

## 📊 Results
- Linear Regression achieved strong prediction performance.
- Lasso Regression reduced less important feature coefficients.
- Ridge Regression helped stabilize coefficients and reduce overfitting.
- TV advertising showed the strongest impact on sales prediction.

---

## 🔍 Key Insights
- TV advertising contributes significantly to product sales.
- Regularization techniques improve model stability.
- Cross-validation confirms model reliability and consistency.
- Multicollinearity among features was analyzed using VIF.

---

## 🚀 Outcome
Successfully developed and evaluated multiple regression models capable of predicting sales based on advertising expenditure with good accuracy and interpretability.

---

## 📁 Project Structure

```text
OIBSIP_Advertising_Sales_Prediction/
│
├── Advertising_Sales_Prediction.ipynb
├── Advertising.csv
├── README.md
