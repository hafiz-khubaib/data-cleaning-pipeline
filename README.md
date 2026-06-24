# 📈 Salary Prediction using Linear Regression

A Supervised Machine Learning project that predicts an employee's salary based on their years of experience. The model is trained on a dataset sourced from Kaggle and evaluated using key regression metrics and data visualization.

---

## 🚀 Project Overview
The goal of this project is to understand the linear relationship between years of professional experience and salary. Using Python's data science stack, we built a predictive model and visualized how the model fits the actual data points.

### 🛠️ Core Steps Implemented
* **Model Training:** Implemented a **Linear Regression** algorithm using Scikit-Learn.
* **Data Visualization:** Built data plots using **Matplotlib** to analyze model behavior.
* **Model Serialization:** Exported the final trained model into a binary `.pkl` file using Joblib for future deployment.

---

## 🤖 Machine Learning Pipeline & Metrics

### 📊 Dataset Variables
* **Independent Variable (X):** `Years_of_Experience`
* **Dependent Variable (Y):** `Salary` (Target)

### 📉 Model Evaluation & Performance
* **R-squared Score:** **0.8914** (Indicates that ~89% of the variance in salary is predictable from experience).
* **Mean Squared Error (MSE):** 55,761,791.31
* **Root Mean Squared Error (RMSE):** 7,467.38
* **Mean Absolute Error (MAE):** 6,692.36

---

## 🖼️ Data Visualization
To check the model accuracy visually, **Matplotlib** was used to generate plots:
* **`plt.scatter` (Scatter Plot):** Used to plot the actual data points showing the true relationship between experience and salary.
* **`plt.plot` (Regression Line):** Used to draw the best-fit prediction line over the data points to show how the model predicts values.

---

## 📂 Repository Structure
* `myLinearmodel.pkl` -> Trained Linear Regression model file.
* `README.md` -> Project documentation.

---

## ⚡ Technical Skills Demonstrated
* **Languages:** Python
* **ML Libraries:** Scikit-Learn (Sklearn), Joblib
* **Data Visualization:** Matplotlib (Pyplot)
* **Core Concepts:** Supervised Learning, Regression Analysis, Model Evaluation Metrics