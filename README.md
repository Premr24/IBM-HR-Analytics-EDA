# IBM HR Analytics: Employee Attrition EDA

## Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the IBM HR Analytics dataset to uncover the driving factors behind employee turnover. 

## Technical Highlights
* **Libraries Used:** Python, Pandas, Matplotlib, Seaborn
* **Data Cleaning:** Removed zero-variance features to reduce noise.
* **Analysis:** Utilized boxplots and correlation heatmaps to identify mathematical relationships between features like Income, Age, Commute Distance, and Attrition.
* **Machine Learning Prep:** Applied One-Hot Encoding (`pd.get_dummies`) to transform all categorical text data into a fully numeric, machine-learning-ready pipeline.

## Key Business Insights
1. **Income & Age:** Turnover is heavily concentrated among younger, lower-paid employees.
2. **The Commute Factor:** Distance from home had the highest positive correlation with leaving.
3. **Complexity:** No single factor perfectly predicts attrition, highlighting the need for multi-variable predictive modeling.

## Files
* `ibm-hr-analytics-employee-attrition-dataset.ipynb`: The complete Python notebook containing all code and visualizations.
* `WA_Fn-UseC_-HR-Employee-Attrition.csv`: The original dataset.
