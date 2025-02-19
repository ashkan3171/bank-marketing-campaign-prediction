# 📊 Bank Marketing Campaign Success Prediction

## 🚀 Project Overview
This project predicts the success of a **bank marketing campaign** using machine learning.  
We explore different models and techniques to improve accuracy and recall,  
especially given the **imbalanced dataset**.  

🔹 **Dataset**: The dataset contains customer details and past interactions with the bank.  
🔹 **Goal**: Predict whether a customer will **subscribe** (`yes/no`).  
🔹 **Techniques Used**:
   - Exploratory Data Analysis (EDA)
   - Feature Engineering & Data Preprocessing
   - Handling Imbalanced Data using **SMOTE**
   - Model Training: **Logistic Regression, Random Forest, XGBoost**
   - Hyperparameter Tuning with **RandomizedSearchCV**
   - Evaluation using **Precision, Recall, F1-Score, and ROC-AUC**

---

## 🛠️ Project Workflow
1️⃣ **Data Loading & Exploration**
   - Checked for missing values and outliers
   - Analyzed target variable imbalance  
   
2️⃣ **Feature Engineering**
   - Converted categorical features using **One-Hot & Ordinal Encoding**
   - Scaled numerical features using **StandardScaler**
   - Created new features (`pdays_category`, `previous_category`, `balance_category`)

3️⃣ **Handling Imbalanced Data**
   - Used **SMOTE** to balance the dataset
   - Stratified Train-Test Split  

4️⃣ **Model Training & Evaluation**
   - **Logistic Regression** (Baseline Model)
   - **Random Forest** (Better precision-recall balance)
   - **XGBoost** (Final model with the best trade-off)
   - Tuned **hyperparameters** for optimal performance  

---

## 🏆 Model Performance Summary
| Model  | Accuracy | Precision (Yes) | Recall (Yes) | F1-Score (Yes) |
|--------|---------|----------------|-------------|-------------|
| Logistic Regression | 85% | 42% | **81%** | 55% |
| Random Forest | 90% | 58% | **55%** | **56%** |
| XGBoost | 90% | **59%** | 54% | **56%** |

---
