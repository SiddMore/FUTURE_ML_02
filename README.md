# 🏦 Customer Churn Prediction

![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange?style=flat-square)
![Model](https://img.shields.io/badge/Model-XGBoost-red?style=flat-square)

## 📄 Project Overview
This project aims to predict **Customer Churn** (whether a customer will leave the bank or stay) based on their demographic and financial data. By identifying at-risk customers early, banks can implement retention strategies to reduce losses.

This project was developed as a machine learning task for **Future Interns**, utilizing **XGBoost** for high-performance classification.

## 🛠️ Tech Stack
* **Language:** Python 🐍
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, XGBoost
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Dataset Features
The model analyzes the following key customer attributes to determine the likelihood of exit:

| Feature | Description |
| :--- | :--- |
| **CreditScore** | The customer's credit score. |
| **Geography** | Country of residence (France, Spain, Germany). |
| **Gender** | Male or Female. |
| **Age** | Age of the customer. |
| **Tenure** | Number of years the customer has been with the bank. |
| **Balance** | Account balance. |
| **NumOfProducts** | Number of bank products the customer uses. |
| **HasCrCard** | Whether the customer holds a credit card (1=Yes, 0=No). |
| **IsActiveMember** | Activity status of the customer (1=Active, 0=Inactive). |
| **EstimatedSalary** | The customer's estimated annual salary. |

## 🚀 Model Performance
The project compares multiple algorithms (Logistic Regression, Random Forest), with **XGBoost** providing the best results.

### 1. Confusion Matrix
*Visualizing how well the model predicts True Positives vs. True Negatives.*


### 2. Classification Report
*A detailed look at Precision, Recall, and F1-Scores for the Churn (1) and No-Churn (0) classes.*

### 3. Visual Analysis
*Additional insights into model performance and feature distribution.*


## 🏁 How to Run Locally

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Install Dependencies**
    ```bash
    pip install pandas matplotlib seaborn sklearn xgboost
    ```

3.  **Run the Notebook**
    ```bash
    jupyter notebook fut-ml-02.ipynb
    ```

---
*Created for Future Interns ML Task*
