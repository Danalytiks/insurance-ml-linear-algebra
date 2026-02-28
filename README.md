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

- Demonstrated how linear algebra supports practical ML workflows  
- Confirmed that predictive models outperform a dummy baseline for classification tasks  
- Built a regression model for payment count estimation  
- Verified that privacy-preserving transformations can protect data without degrading linear regression quality  

---

## 📊 Results

- The classification model outperformed the dummy baseline, confirming predictive value.
- The linear regression model successfully estimated payment counts.
- After applying an invertible linear transformation to the feature matrix, model predictions remained unchanged.
- The privacy-preserving transformation successfully masked sensitive information without degrading model performance.

The experiment demonstrates that linear algebra can be used both for predictive modeling and for secure data transformation.

## 🧰 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
