# Logistic Regression

## 📌 Overview
Logistic Regression is a supervised machine learning algorithm used for **classification tasks**. Unlike linear regression, which predicts continuous values, logistic regression predicts the **probability of a class** (often binary outcomes such as *yes/no*, *spam/not spam*, *disease/no disease*).

It uses the **sigmoid (logistic) function** to map predictions to a range between 0 and 1, making it ideal for classification.

---

## 🔑 Key Concepts
- **Sigmoid Function**  
  \[
sigmoid(z) = 1 / (1 + e^(-z))
  \]  
  Converts linear outputs into probabilities between 0 and 1.

- **Decision Boundary**  
  Probabilities are mapped to classes using a threshold (commonly 0.5).  
  - If probability ≥ 0.5 → Class 1  
  - If probability < 0.5 → Class 0  

- **Loss Function**  
  Logistic regression uses **binary cross-entropy (log loss)** to measure error.

- **Applications**  
  - Spam email detection  
  - Disease diagnosis (predicting if a patient has a disease)  
  - Credit scoring (loan approval)  
  - Customer churn prediction 
