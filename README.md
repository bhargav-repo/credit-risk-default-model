# 🏦 Credit Risk Default Prediction Model

## 📌 Overview
This project builds a classification model to predict the likelihood of credit default based on financial performance indicators. It was completed as part of the **Finance and Risk Analytics** course during my postgraduate program in **Data Science and Business Analytics** at **UT Austin**.

## 🧠 Objective
To classify Indian companies based on whether they are likely to default on loan payments, using historical financial metrics. The target variable is derived from net worth projected for the next year.

## 📊 Dataset
- 4256 records × 51 features
- Financial metrics such as assets, income, capital, liabilities, ratios, and profitability indicators
- Binary target: `default = 1` if net worth next year is negative, else `0`

## ⚙️ Tools & Techniques
- Python, Pandas, Scikit-learn, Statsmodels, Matplotlib, Seaborn
- Logistic Regression, Random Forest Classifier
- Feature selection using VIF (Variance Inflation Factor)
- Outlier treatment & missing value imputation

## 📈 Model Performance
| Model             | Accuracy | Sensitivity |
|------------------|----------|-------------|
| Logistic Regression | ~79%     | 19–21%      |
| Random Forest       | ~80–81%  | 15%         |

> **Note**: Logistic Regression was selected for its interpretability and slightly better sensitivity.

## 🧠 Key Steps
- Data cleaning and imputation using median values
- Outlier treatment with percentile capping
- Correlation matrix and VIF to reduce multicollinearity
- Built 6 logistic models to tune feature sets
- Compared against Random Forest for benchmarking

## 📁 Project Structure
