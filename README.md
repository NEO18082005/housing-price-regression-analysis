# House Price Prediction - Internship Project

This repository contains the Week 1 internship project focused on predicting real estate property values. The goal was to build and compare machine learning regression models to provide data-driven insights for property valuation.

## 🚀 Project Overview
* **Objective:** Build regression models to predict house prices based on features like area, bedrooms, and location.
* **Tools Used:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn.
* **Models Trained:** Linear Regression & Random Forest Regressor.

## 🛠️ Tasks Completed
1. **Data Loading & Exploration:** Initial data assessment to identify features and target variables.
2. **Data Cleaning:** Handled duplicates, addressed missing values, and encoded categorical variables (e.g., 'yes/no' fields to binary).
3. **Model Building:** Trained two models (Linear Regression and Random Forest) to compare performance.
4. **Visualization:** Created distributions, correlation heatmaps, and scatter plots.
5. **Insights & Summary:** Synthesized findings to offer recommendations for real estate decision-making.

## 📊 Performance Metrics
The models were evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.

| Metric | Linear Regression | Random Forest Regressor |
| :--- | :--- | :--- |
| **R² Score** | **0.65** | 0.61 |
| **MAE** | 970,043.40 | 1,022,560.05 |
| **RMSE** | 1,324,506.96 | 1,401,496.84 |

*Note: The Linear Regression model showed slightly higher predictive accuracy (R²: 0.65), suggesting that the dataset features have a strong linear relationship with price.*

## 📁 Repository Structure
- `analysis.ipynb`: Complete Jupyter Notebook containing all 5 tasks.
- `Housing.csv`: The raw dataset used for analysis.
- `summary.pdf`: A 1-page summary report of findings.
- `charts/`: Folder containing the 3 generated visualizations in .png format.
