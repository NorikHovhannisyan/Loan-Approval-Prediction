# 🧠 Loan Approval Prediction using Neural Networks

This project predicts whether a loan application should be **approved or rejected** using a **Neural Network model** built with Python and deep learning frameworks.

---

## 📌 Overview

Financial institutions receive thousands of loan applications daily, and manual evaluation can be time-consuming and inconsistent.  
This project automates the loan approval process by training a neural network on historical loan data to predict approval decisions.

---

## ⚙️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy, Pandas**
- **Matplotlib / Seaborn**
- **Scikit-learn**

---

## 🧾 Dataset

The dataset contains information about loan applicants, such as:

| Feature | Description |
|----------|--------------|
| **id** | Unique identifier for each applicant |
| **person_age** | Applicant’s age |
| **person_income** | Applicant’s annual income |
| **person_home_ownership** | Type of home ownership (e.g., rent, own, mortgage) |
| **person_emp_length** | Years of employment |
| **loan_intent** | Purpose of the loan (education, medical, debt consolidation, etc.) |
| **loan_grade** | Loan quality grade assigned by the lender |
| **loan_amnt** | Loan amount requested |
| **loan_int_rate** | Interest rate of the loan |
| **loan_percent_income** | Ratio of loan amount to applicant’s income |
| **loan_status (target)** | 1 = Approved, 0 = Rejected *(target variable)*

---

## ⚙️ Data Preprocessing

- Filled missing values  
- Encoded categorical columns (`person_home_ownership`, `loan_intent`, `loan_grade`) using **Label Encoding / One-Hot Encoding**  
- Scaled numerical features (`person_age`, `person_income`, `loan_amnt`, etc.)  
- Split data into **train/test sets**  

---

---

## 🧠 Model Architecture

A **Feed-Forward Neural Network (Fully Connected Layers)** was implemented using **Keras**.
____________________________________________________________________________________________________________________________________________________________________

## 📈 Results

• Achieved around 92% accuracy on the test set (replace with your actual result).
• The model successfully captures patterns related to credit history, income, and property area.

## 🚀 How to Run

1. Clone this repository

`git clone [https://github.com/<your-username>/Loan-Approval-Prediction.git](https://github.com/NorikHovhannisyan/Loan-Approval-Prediction.git)`

2. Install dependencies

`pip install -r requirements.txt`


3. Run the notebook

`jupyter notebook Loan_approval.ipynb`
