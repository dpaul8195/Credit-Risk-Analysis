# 📊 Credit Risk Analysis  

## 🔍 Introduction  
Credit risk modelling is the process of estimating the potential losses a financial institution may face if a borrower defaults on their loan. These models are widely used by banks, NBFCs, and lending platforms to assess the **probability of default (POD)** and guide key lending decisions such as:  

- Whether to approve or reject a loan application.  
- How much credit to extend.  
- At what interest rate to lend.  

Accurately identifying credit risk helps lenders **minimize defaults and safeguard funds**.  

---

## 📂 Dataset  
The dataset used for this project is sourced from **[Kaggle](https://www.kaggle.com/)**.  
It contains borrower-related and loan-related attributes, including:  

- **Demographic features**: Age, Income, Employment Length, Home Ownership.  
- **Loan features**: Interest Rate, Loan Purpose, Loan Amount, etc.  
- **Target variable**: Credit risk classification (default vs non-default).  

---

## ⚙️ Project Workflow  
The project follows a complete machine learning pipeline:  

### 1. Exploratory Data Analysis (EDA)  
- **Univariate analysis**: Distribution of age, income, loan amounts, etc.  
- **Bivariate analysis**: Relationship between features (e.g., income vs. loan default).  
- **Target analysis**: Class imbalance check for default vs non-default borrowers.  

### 2. Data Preprocessing & Feature Engineering  
- **Handling Missing Values**: Imputed numerical and categorical columns using appropriate strategies.  
- **Outlier Treatment**: Detected and capped extreme values for robust model performance.  
- **Feature Encoding**: Converted categorical variables into numerical form.  
- **Feature Scaling**: Standardized/normalized features where necessary.  

### 3. Dealing with Imbalanced Data  
- Applied resampling techniques such as **SMOTE** and **undersampling** to balance the dataset.  

### 4. Model Training & Evaluation  
Trained and compared multiple machine learning algorithms:  
- ✅ Logistic Regression  
- ✅ K-Nearest Neighbors (KNN)  
- ✅ Decision Trees  
- ✅ Random Forest  
- ✅ Support Vector Machine (SVM)  
- ✅ XGBoost  

### 5. Model Evaluation Metrics  
- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- ROC-AUC Curve  

---

## Run
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dpaul8195/Credit-Risk-Analysis/blob/main/CreditRiskModelling.ipynb)
---

## 📈 Results  
- **Random Forest** and **XGBoost** emerged as the best-performing models.  
- Random Forest achieved **93% accuracy**, robustly handling class imbalance.  
- XGBoost provided competitive performance with better efficiency on large datasets.  

---

## 📝 Conclusion  
- Ensemble models (**Random Forest, XGBoost**) outperform simpler models for credit risk prediction.  
- Proper **EDA, feature engineering, and handling missing values/outliers** significantly improve results.  
- The project demonstrates how machine learning supports **data-driven lending decisions**.  

---

## 🚀 Future Work  
- Experimenting with **Neural Networks and Deep Learning approaches**.  
- Performing **explainability analysis (SHAP, LIME)** for model transparency.  
- Deploying the final model as a **web-based credit risk prediction tool**.  

---

## 📌 Summary  
This project provides a structured approach to **credit risk modelling**, including:  

✔ Exploratory Data Analysis (EDA)  
✔ Handling Missing Values & Outliers  
✔ Feature Engineering & Class Imbalance Treatment  
✔ Model Comparison across Logistic Regression, KNN, Decision Trees, Random Forest, SVM, and XGBoost  
✔ Random Forest achieved the best performance with **93% accuracy**  

---
