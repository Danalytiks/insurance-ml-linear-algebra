# 🧮 Linear Algebra for Machine Learning – Insurance Use Case  
Similarity Search, Classification, Regression & Privacy-Preserving Transformation

---

## 📖 Project Overview

This project evaluates the feasibility of solving multiple business tasks for an insurance company using machine learning and linear algebra concepts. The work includes customer similarity search for marketing, churn/claim-related classification, regression modeling for payment count prediction, and a privacy-preserving data transformation technique designed to protect personal information without reducing model performance.

---

## 🎯 Business Objectives

- Identify customers similar to a given customer to support targeted marketing  
- Predict whether a new customer is likely to receive an insurance payment (and compare against a dummy baseline)  
- Predict the expected number of insurance payments using linear regression  
- Apply a privacy-preserving transformation to sensitive data while maintaining model quality  

---

## 🛠️ Methodology

### 1️⃣ Similarity Search (KNN-style logic)
- Feature scaling and distance-based similarity computation  
- Retrieval of nearest customers for marketing insights  

### 2️⃣ Binary Classification (Payment Likelihood)
- Baseline comparison using a dummy model  
- Evaluation using appropriate classification metrics  

### 3️⃣ Linear Regression (Payment Count Prediction)
- Train a linear regression model to estimate expected number of payments  
- Performance comparison using regression metrics  

### 4️⃣ Privacy-Preserving Transformation
- Apply an invertible linear transformation (matrix-based) to anonymize feature space  
- Demonstrate that model predictions and performance remain consistent after transformation  
- Validate that original sensitive values are not directly recoverable without the transformation key  

---

## ✅ Key Outcomes

- Applied linear algebra concepts to practical machine learning workflows  
- Evaluated model performance against a baseline classifier  
- Implemented linear regression for payment count estimation  
- Designed and validated a privacy-preserving data transformation approach
---

## 📊 Results

- Classification model outperformed the dummy baseline.  
- Linear regression successfully estimated payment counts.  
- Predictions remained unchanged after applying an invertible linear transformation.  
- Sensitive data was effectively masked without degrading model performance.

The experiment demonstrates that linear algebra can be used both for predictive modeling and for secure data transformation.

## 🧰 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
