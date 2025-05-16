# Customer Churn Prediction Using Machine Learning

## 📖 Description
This project aims to predict customer churn in a telecom company using machine learning. It includes data cleaning, exploratory data analysis (EDA), handling imbalanced data using SMOTE, model building using Random Forest, and model evaluation. The goal is to help telecom companies identify customers likely to churn and take proactive steps to retain them.

## 🗂️ Dataset
- Dataset: WA_Fn-UseC_-Telco-Customer-Churn.csv  
- Source: IBM Sample Dataset  
- Size: ~7000 records  
- Features: Demographics, service usage, billing info, and churn status  

## 🧹 Data Cleaning
- Dropped irrelevant column: `customerID`  
- Converted `TotalCharges` to numeric and filled missing values  
- Applied label encoding to convert categorical variables to numeric  

## 📊 Exploratory Data Analysis
- Analyzed churn distribution  
- Created a correlation heatmap to understand relationships between features  
- Visualized important feature trends  

## ⚖️ Handling Imbalanced Data
Used SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset, ensuring the model learns effectively from both churned and non-churned customers.

## 🔄 Feature Scaling
Standardized the feature values using StandardScaler to bring all features to the same scale and improve model performance.

## 🧠 Model Building
- Model: Random Forest Classifier  
- Tuned parameters:  
  - `n_estimators=200`  
  - `max_depth=10`  
  - `min_samples_split=10`  
  - `min_samples_leaf=4`  
- Trained the model on a balanced and scaled dataset  

## 🧪 Model Evaluation
- Accuracy Score on test data  
- Confusion Matrix  
- ROC Curve and AUC Score  
- Classification Report (Precision, Recall, F1-Score)  
- Feature Importance analysis  

