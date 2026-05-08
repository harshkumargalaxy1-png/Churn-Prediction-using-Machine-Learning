# 📉 Customer Churn Prediction using Machine Learning

This project implements an end-to-end Machine Learning pipeline to predict customer churn. By identifying at-risk customers, businesses can proactively implement retention strategies. This solution features extensive EDA and a highly optimized LightGBM model.

---

### 📋 Project Workflow

1.  **Data Ingestion:** Reading and structured parsing of the Customer Churn Dataset.
2.  **Exploratory Data Analysis (EDA):** 
    *   Visualizing churn distribution and feature correlations.
    *   Identifying key drivers of customer attrition (e.g., contract type, monthly charges).
    *   Outlier detection and missing value analysis.
3.  **Feature Engineering:** Encoding categorical variables and scaling numerical features for gradient boosting performance.
4.  **Model Building:** Implementing and comparing various algorithms with a focus on **LightGBM**.
5.  **Hyperparameter Optimization:** Fine-tuning the LightGBM model using advanced optimization techniques to maximize predictive power.

---

### 📊 Results & Performance
Through rigorous hyperparameter tuning, the final model achieved significant predictive accuracy:

> **Final Model:** LightGBM  
> **Primary Metric:** **AUC 0.87**

This high AUC score indicates a strong ability to distinguish between churning and loyal customers, providing a reliable tool for business decision-making.

---

### 🛠️ Tools & Technologies
*   **Language:** Python
*   **Data Analysis:** Pandas, NumPy
*   **Visualization:** Matplotlib, Seaborn
*   **Machine Learning:** LightGBM, Scikit-learn
*   **Optimization:** Optuna / GridSearch / RandomizedSearch
*   **Environment:** Jupyter Notebook / GitHub

---

