# 💳 CreditWise Loan Approval System

CreditWise is a supervised machine learning project that focuses on building an intelligent **Loan Approval System**. The objective of this project is to predict whether a loan application should be approved or rejected based on applicant details and financial attributes.

The project follows a complete end-to-end machine learning workflow, from data preprocessing and exploratory analysis to model training, evaluation, and performance improvement.

---

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

## 📁 Project Structure

```
CreditWise/
├── CreditWise_Loan_System.ipynb        # Main Jupyter Notebook (full ML pipeline)
├── loan_approval_data.csv   # Dataset with 1000 loan applicant records
├── requirements.txt         # Python dependencies
|-- CreditWise_Loan_System.pdf
└── README.md
```

---
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
1. Data Import and Inspection  
2. Handling Missing Values  
3. Exploratory Data Analysis (EDA)  
4. Data Visualization  
5. Feature Encoding (Categorical to Numerical)  
6. Correlation Analysis using Heatmap  
7. Train-Test Split  
8. Feature Scaling  
9. Model Training and Evaluation  
10. Feature Engineering  
11. Model Re-training and Performance Improvement  
12. Final Model Selection  


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
- Implement Random Forest and other ensemble methods
- Perform hyperparameter tuning
- Deploy the model as a web-based loan approval system
- Use real-time applicant data for predictions


## 🏆 Final Recommendation
The **Balanced Random Forest model with a stricter approval threshold**
provides the best trade-off between business risk and model performance.

This model is recommended as a **decision support system** to assist loan officers,
not replace them.


## ⚖️ Ethical & Business Considerations
- Ensures fair and consistent decision-making
- Reduces human bias
- Maintains human-in-the-loop approval authority


## ⚙️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/vivekpatil/CreditWise_Loan_System.git
   cd CreditWise_Loan_System
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook CreditWise_Loan_System.ipynb
   ```

4. Make sure `loan_approval_data.csv` is in the same directory as the notebook.

---

## 🎓 Conclusion

> ✅ **Best Model: Naive Bayes** — selected based on highest Precision score, which minimises false approvals (high-risk customers being incorrectly approved).

This project demonstrates a complete, real-world machine learning workflow that
aligns technical model performance with business objectives in the financial
domain. It highlights the importance of risk-aware evaluation and ethical ML
deployment in loan approval systems.

## 👤 Author

**Vivek Patil**  
📧 vivekp9356@gmail.com  
🔗 [GitHub – Vivek Patil](https://github.com/vivekk-patil)
