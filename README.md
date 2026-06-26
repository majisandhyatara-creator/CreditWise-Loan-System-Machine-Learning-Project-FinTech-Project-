# CreditWise-Loan-System-Machine-Learning-Project-FinTech-Project-
Built an end-to-end supervised ML pipeline using KNN, Logistic Regression, and Naive Bayes to predict loan approval.  Implemented binary classification along with Exploratory Data Analysis (EDA), feature engineering, and model evaluation (Precision, Recall, F1-Score).

# CreditWise: Loan Approval Prediction System

CreditWise is an end-to-end supervised machine learning pipeline designed to automate and optimize the credit risk assessment process. By analyzing historical applicant data, the system predicts whether a loan application should be approved or rejected using binary classification algorithms.

##  Project Overview
In the traditional banking sector, manually evaluating creditworthiness is time-consuming and prone to human error. CreditWise leverages Machine Learning to streamline this workflow, ensuring faster processing times and data-driven risk management.

### Key Features Implemented:
* **Exploratory Data Analysis (EDA):** Detailed data profiling, distribution checking, and multicollinearity analysis using correlation heatmaps.
* **Data Preprocessing & Cleaning:** Advanced handling of missing values, outlier detection, and categorical feature encoding.
* **Feature Engineering & Scaling:** Optimizing features to boost algorithm convergence and performance.
* **Predictive Modeling:** Training and tuning multiple classification algorithms, including K-Nearest Neighbors (KNN), Logistic Regression, and Naive Bayes.
* **Model Evaluation:** Robust evaluation using Precision, Recall, and F1-Score metrics to minimize financial risk (false positives).

---

##  Tech Stack & Libraries
* **Language:** Python
* **Environment:** JupyterLab / Jupyter Notebook
* **Libraries:** * Data Manipulation: `pandas`, `numpy`
  * Data Visualization: `matplotlib`, `seaborn`
  * Machine Learning: `scikit-learn`

---

##  Project Pipeline Structure
The project workflow follows a structured machine learning lifecycle as taught in the *Prime 2.0: AI/ML Batch*:

1. **Data Ingestion:** Loading the credit dataset.
2. **Handling Missing Data:** Imputing missing attributes systematically.
3. **Exploratory Data Analysis (EDA):** Visualizing patterns and identifying correlations.
4. **Feature Encoding & Scaling:** Converting categorical data to numerical and applying feature scaling.
5. **Model Training & Evaluation:** Implementing KNN, Logistic Regression, and Naive Bayes.
6. **Model Fine-Tuning:** Feature engineering adjustments to maximize the F1-Score.

---

##  Model Evaluation Summary
*(Note: Replace these placeholder values with your actual project results!)*

| Model | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- |
| **Logistic Regression** | 0.84 | 0.81 | 0.82 |
| **K-Nearest Neighbors** | 0.79 | 0.75 | 0.77 |
| **Naive Bayes** | 0.81 | 0.83 | 0.82 |

---

##  How to Run This Project Local
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/CreditWise-Loan-System.git](https://github.com/YOUR_USERNAME/CreditWise-Loan-System.git)
