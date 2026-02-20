# 🏥 Healthcare Premium Prediction System
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-red)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-success)

An end-to-end **Machine Learning Regression Project** that predicts **Annual Healthcare Insurance Premiums** based on customer demographic and financial attributes.

🔗 **Live App:**  
https://mlhealthpremiumprediction.streamlit.app/

---
# 📌 Project Overview

Insurance companies must accurately estimate annual premium amounts based on customer risk profiles.

This project builds a complete ML pipeline to:

- Analyze customer data  
- Identify premium-driving factors  
- Train multiple regression models  
- Compare performance  
- Deploy prediction system 
---

## 🚀 Features

- Predict **Annual Premium Amount** using ML models  
- Perform detailed **Exploratory Data Analysis (EDA)**  
- Compare multiple regression algorithms  
- Identify key factors affecting premium pricing  
- Analyze extreme prediction errors  
- Modular and scalable project structure  
- Deployment-ready architecture  

---

## 🎯 Problem Statement

Insurance companies require accurate estimation of annual premium amounts based on customer details.

This system predicts:

> **Annual Premium Amount**

Using features such as:
- Age  
- Annual Income (in lakhs)  
- Number of Dependants  
- Insurance Plan Type  
- Income Level  

This is a **Supervised Regression Problem**.

---

## 📊 Dataset Description

The dataset contains structured customer-level insurance data.

### 🔹 Features

| Feature Name | Description |
|--------------|------------|
| age | Age of the customer |
| income_lakhs | Annual income in lakhs |
| number_of_dependants | Number of dependants |
| insurance_plan | Type of insurance plan selected |
| income_level | Encoded income category |
| annual_premium_amount | Target variable |

### 🔹 Data Preprocessing

- Handling missing values  
- Encoding categorical variables  
- Feature scaling using StandardScaler  
- Outlier inspection  
- Reverse scaling for real-world interpretation  

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was performed using:

- Scatter plots  
- Distribution plots  
- Correlation analysis  
- Feature vs target visualization  

### 📌 Key Insights

- Income strongly influences premium amount  
- Insurance plan significantly impacts pricing  
- Age shows weak linear relationship in this dataset  
- Certain income-plan combinations produce higher prediction variance  

---

## 🤖 Models Implemented

The following regression models were trained and compared:

1. Linear Regression  
2. Random Forest Regressor  
3. XGBoost Regressor  

---

## 📈 Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

### 📊 Model Comparison (Example Format)

| Model | RMSE | R² Score |
|--------|------|----------|
| Linear Regression | — | — |
| Random Forest | — | — |
| XGBoost | — | — |

The best model was selected based on lowest RMSE and highest R² score.

---

## 🔎 Error Analysis

To better understand model behavior:

- Identified extreme prediction errors  
- Reversed scaled features to interpret real-world values  
- Analyzed customer segments contributing to higher errors  

This improved model interpretability and business understanding.

---

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone .https://github.com/AngadiAbhinay01/ML_Health_Premium_Predictiongit
   cd healthcare-premium-prediction
   ```
2. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
3. **Run jupyter notebook:**:   
   ```commandline
    jupyter notebook
   ```
4. **Run the Streamlit app:**:   
   ```commandline
    https://mlhealthpremiumprediction.streamlit.app/
   ```
---

## 🛠 Tech Stack

- **Python 3.10+** – Core programming language  
- **Pandas** – Data manipulation and preprocessing  
- **NumPy** – Numerical computations  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical data visualization  
- **Scikit-learn** – Machine learning models and preprocessing  
- **XGBoost** – Gradient boosting regression model  
- **Jupyter Notebook** – Model development and experimentation  
- **Streamlit** – Interactive frontend deployment (optional)  

---

## 💡 Key Learnings

- Importance of proper data preprocessing before model training  
- Feature scaling significantly impacts regression performance  
- Comparing multiple models improves reliability and robustness  
- Exploratory Data Analysis (EDA) helps uncover hidden data patterns  
- Reverse scaling improves real-world interpretability of predictions  
- Model evaluation metrics (RMSE, R²) must be interpreted together  

---

## 🔮 Future Enhancements

- Hyperparameter tuning using GridSearchCV or RandomSearchCV  
- Implement K-Fold Cross Validation for robust evaluation  
- Add SHAP for model explainability  
- Build REST API using FastAPI or Flask  
- Deploy on AWS / GCP / Azure  
- Add additional real-world health risk features  
- Implement automated model monitoring  

---

## 👨‍💻 Author

**Abhinay Angadi**  

📧 Email: angadiabhinay2001@gmail.com  
💼 LinkedIn: https://linkedin.com/in/abhinay-angadi-541004159  
💻 GitHub: https://github.com/AngadiAbhinay01

---
---

## ⭐ If You Found This Project Helpful

If you found this project useful or insightful, please consider giving it a ⭐ on GitHub.  
Your support helps increase visibility and encourages further improvements!

---
