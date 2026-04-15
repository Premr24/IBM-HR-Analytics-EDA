# 📊 IBM HR Analytics: Predicting Employee Attrition

## 🎯 Project Objective
Employee turnover is a major cost for modern enterprises. The goal of this project is to analyze a comprehensive HR dataset, uncover the root causes of employee attrition, and build a predictive machine learning model to flag high-risk employees before they leave.

## 🧠 Strategic Approach: Domain-Driven Feature Engineering
Rather than relying solely on raw demographic data, this project emphasizes **domain-specific feature engineering** to capture the compound, human reasons why employees quit. Key engineered features include:
* **Flight Risk Index:** An interaction feature combining commute distance and job satisfaction to measure compound stress.
* **Promotion Stagnation:** A ratio measuring the time since an employee's last promotion against their total tenure.
* **Managerial Churn:** Calculating years spent under previous management to detect recent, disruptive leadership changes.
* **Tenure Bands:** Grouping raw employment years into distinct career stages (e.g., Newcomer, Veteran).

## 🛠️ Technical Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest Classifier)
* **Techniques:** Exploratory Data Analysis (EDA), Data Cleaning, One-Hot Encoding, Feature Engineering, Model Evaluation (Recall, Feature Importance)

## 📈 Key Insights & Business Recommendations
Our Random Forest model successfully identified the true drivers of attrition, outperforming raw data baselines:

1. **Compound Stress is the #1 Trigger:** The engineered `Flight_Risk_Index` emerged as the most critical driver of attrition. 
   * *Recommendation:* Implement targeted remote-work options for employees with long commutes to instantly reduce flight risk.
2. **The Compensation Baseline:** `MonthlyIncome` remains a highly significant factor. 
   * *Recommendation:* Proactively cross-reference salaries of high-performing employees flagged by the model against current market rates.
3. **The Burnout Factor:** Employees assigned `OverTime` represent a massive risk category.
   * *Recommendation:* Treat consistent departmental overtime as a signal to hire more headcount rather than a metric of high productivity.

## 🚀 How to Run the Project
1. Clone this repository.
2. Ensure you have the required libraries installed (`pip install pandas numpy matplotlib seaborn scikit-learn`).
3. Run the `ibm-hr-analytics-employee-attrition-dataset.ipynb` Jupyter Notebook to view the full pipeline, from raw data to the final feature importance chart.

## 🔗 Project Link
[View the full Kaggle Notebook](https://www.kaggle.com/code/premarp/ibm-hr-analytics-employee-attrition-updated)

---
**Connect with me:** [LinkedIn](https://www.linkedin.com/in/prem-rawal/) | [GitHub](https://github.com/Premr24)
