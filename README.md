# 💳 CreditWise Loan Approval System

## 📌 Project Overview
CreditWise is a **Machine Learning–based loan approval decision support system**
designed to help financial institutions predict whether a loan application should
be **Approved or Rejected** based on applicant financial, employment, and credit data.

The system aims to reduce manual effort, bias, and financial risk while ensuring
faster and more consistent loan approval decisions.


## 🧠 Problem Statement
Traditional loan approval processes rely heavily on manual verification by loan
officers, which can be:
- Time-consuming
- Biased
- Inconsistent

As a result:
- Creditworthy applicants may be rejected
- High-risk applicants may be approved, causing financial losses

This project addresses these challenges by leveraging **Supervised Machine Learning**
to assist in loan approval decisions.


## 🎯 Objective
- Predict whether a loan should be **Approved (1)** or **Rejected (0)**
- Minimize financial risk by correctly identifying high-risk applicants
- Support human decision-making with data-driven insights


## 📂 Dataset Description
Each row in the dataset represents a **loan applicant** with personal, financial,
employment, and credit-related attributes.

### 🔑 Key Features
- Applicant & Coapplicant Income
- Employment Status
- Credit Score
- Debt-to-Income (DTI) Ratio
- Existing Loans
- Savings & Collateral Value
- Loan Amount & Loan Term
- Property Area & Loan Purpose
- Education Level & Marital Status

### 🎯 Target Variable
- `Loan_Approved`
  - `1` → Approved  
  - `0` → Rejected  


## ⚙️ Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn


## 🔄 Machine Learning Workflow
1. Data loading and exploration (EDA)
2. Data preprocessing and cleaning
3. Handling missing values
4. Encoding categorical variables
5. Feature scaling
6. Train-test split
7. Model training and comparison
8. Risk-aware evaluation and optimization


## 🤖 Models Implemented
- **Logistic Regression** (Baseline & Balanced)
- **Decision Tree Classifier**
- **Random Forest Classifier** (Balanced & Tuned)


## 📊 Model Evaluation Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### 🔍 Key Evaluation Insight
In loan approval systems, **recall for rejected loans** is more critical than
overall accuracy, as approving a high-risk applicant can lead to significant
financial losses.


## 🚀 Advanced Improvements
- Class imbalance handled using `class_weight='balanced'`
- Feature scaling to improve model convergence
- Probability-based predictions
- Custom threshold tuning to reduce risky approvals
- Feature importance analysis for interpretability


## 🏆 Final Recommendation
The **Balanced Random Forest model with a stricter approval threshold**
provides the best trade-off between business risk and model performance.

This model is recommended as a **decision support system** to assist loan officers,
not replace them.


## ⚖️ Ethical & Business Considerations
- Ensures fair and consistent decision-making
- Reduces human bias
- Maintains human-in-the-loop approval authority



## ▶️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/creditwise-loan-system.git
2. Open Jupyter Notebook:
   jupyter notebook
3. Run Creditwise_Loan_System.ipynb

## 🎓 Conclusion

This project demonstrates a complete, real-world machine learning workflow that
aligns technical model performance with business objectives in the financial
domain. It highlights the importance of risk-aware evaluation and ethical ML
deployment in loan approval systems.

