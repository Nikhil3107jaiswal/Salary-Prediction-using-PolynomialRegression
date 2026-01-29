# 💰 Salary Prediction using Linear & Polynomial Regression

## 📌 Project Overview
This project demonstrates how **machine learning regression techniques** can be used to predict employee salaries based on job seniority levels.  
It simulates a **real-world HR salary negotiation use case**, where data-driven decisions are required to offer fair and competitive compensation.

The project compares **Linear Regression** and **Polynomial Regression** to identify the best-performing model for non-linear salary trends.

---

## 🎯 Business Problem
The HR team maintains a salary structure based on employee levels.

📍 Scenario:
- A candidate applies for the role of **Regional Manager**
- Falls between **Level 6 and Level 7**
- Assumed level: **6.5**
- Goal: **Predict the optimal salary to offer**

---

## 📊 Dataset Information
**Dataset Name:** `Position_Salaries.csv`

**Columns:**
- `Position` – Job role (categorical)
- `Level` – Seniority level (numerical)
- `Salary` – Annual salary (target variable)

This dataset represents approximate salary ranges for different organizational levels.

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🧠 Machine Learning Approach

### 1️⃣ Linear Regression
- Assumes a linear relationship between level and salary
- Easy to interpret
- Results in **underfitting** due to non-linear salary growth

### 2️⃣ Polynomial Regression
- Captures non-linear trends effectively
- Polynomial degree = **4**
- Provides a smooth curve that closely fits the data

---

## 📈 Model Evaluation Metrics
To evaluate model performance, the following metrics were used:

- **R² Score** – Measures goodness of fit
- **RMSE (Root Mean Squared Error)** – Measures prediction error

### 🔍 Results Summary
| Model | Performance |
|-----|------------|
| Linear Regression | Poor fit (Underfitting) |
| Polynomial Regression | High accuracy & low error |

✅ **Polynomial Regression outperformed Linear Regression significantly**

---

## 💡 Key Insights
- Salary progression is **non-linear** with respect to job level
- Linear models fail to capture exponential growth
- Polynomial Regression provides **realistic and reliable predictions**
- Model can be used as a **decision-support system for HR teams**

---

## 💼 Business Impact
- Enables **fair and data-driven salary negotiations**
- Prevents underpaying or overpaying candidates
- Improves transparency in HR compensation strategies
- Reduces bias in salary decision-making

---

## 🚀 Final Recommendation
**Polynomial Regression** is the preferred model for predicting employee salaries in this scenario due to:
- Higher accuracy
- Better fit
- Real-world applicability

---

## 📁 Project Structure
