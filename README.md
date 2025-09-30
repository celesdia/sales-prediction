# sales-prediction
"A data science project to predict future sales using regression and time-series models. Includes data cleaning, feature engineering, visualization, and insights for business strategy."
# 📊 Sales Prediction using Python

## 📌 Project Overview

This project focuses on predicting sales based on advertising spend across three channels: **TV, Radio, and Newspaper**. The goal is to identify which advertising platforms contribute the most to sales and provide actionable insights for businesses to optimize their marketing strategies.

## 🎯 Objectives

* Prepare and clean the dataset for analysis.
* Explore relationships between advertising spend and sales.
* Build and evaluate a **Linear Regression model** to forecast sales.
* Analyze how changes in advertising budgets impact sales outcomes.
* Deliver business recommendations for effective budget allocation.

## 🛠️ Tools & Libraries

* **Python**
* **Pandas** → Data handling and cleaning
* **Matplotlib & Seaborn** → Data visualization
* **Scikit-learn** → Machine learning model (Linear Regression)

## 📂 Dataset

The dataset (*Advertising.csv*) includes:

* `TV`: Advertising spend on TV
* `Radio`: Advertising spend on Radio
* `Newspaper`: Advertising spend on Newspaper
* `Sales`: Units sold (target variable)

## 🚀 Steps Implemented

1. **Data Preparation** – Removed unnecessary columns and checked for missing values.
2. **Exploratory Data Analysis** – Used scatterplots and heatmaps to identify correlations.
3. **Feature Selection** – Chose `TV`, `Radio`, and `Newspaper` as predictors.
4. **Model Building** – Trained a Linear Regression model using scikit-learn.
5. **Evaluation** – Measured performance using R² Score and Mean Squared Error.
6. **Impact Analysis** – Determined which advertising medium had the most influence.
7. **Forecasting** – Predicted sales based on hypothetical advertising budgets.

## 📈 Results

* **TV** has the strongest impact on sales.
* **Radio** also contributes positively.
* **Newspaper** has minimal effect on sales.
* The model achieved an **R² Score of ~0.90**, indicating strong predictive power.

## 💡 Business Insights

* Increase investment in **TV and Radio advertising**.
* Reduce spending on **Newspaper**, as it adds little value.
* Use the regression model for **budget planning and sales forecasting**.

## 🔮 Future Improvements

* Include additional features (online ads, seasonal factors, competitor data).
* Experiment with advanced models (Polynomial Regression, Time Series Forecasting).
* Deploy the model as a simple web app for interactive predictions.

---

📌 *This project demonstrates how data-driven decisions can improve marketing strategies by reallocating budgets to maximize sales impact.*
