# Telco Customer Churn Analysis and Prediction

AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026 (BharatCares)

## Project Description
Customer churn costs telecom companies a lot of revenue. This project explores the IBM Telco Customer Churn dataset to find what drives customers to leave, and trains machine learning models to predict which customers are likely to churn so retention teams can act early.

## Dataset
- **Name:** Telco Customer Churn (IBM sample data)
- **Link:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- **File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv` (about 7,000 customers, 21 columns including contract type, tenure, services, charges and churn label)

## Technologies Used
- Python 3.10+
- pandas, NumPy for data handling
- Matplotlib, Seaborn for visualisation
- scikit-learn for modelling (Logistic Regression, Random Forest)
- Jupyter Notebook

## Project Workflow
1. Load and clean the data (fix `TotalCharges`, drop `customerID`)
2. Exploratory data analysis (churn rate, contract, internet service, payment method, tenure, charges)
3. Feature encoding and scaling, stratified 80/20 train-test split
4. Train and compare Logistic Regression and Random Forest
5. Evaluate with accuracy, precision, recall, F1, ROC-AUC and confusion matrices
6. Feature importance and business recommendations

## Setup and Run
```bash
git clone <https://github.com/SUDHARSAN-2007/telco-churn-analysis>
cd <https://github.com/SUDHARSAN-2007/telco-churn-analysis>
pip install -r requirements.txt
# place WA_Fn-UseC_-Telco-Customer-Churn.csv in this folder
jupyter notebook ChurnAnalysis.ipynb
```
Run all cells from top to bottom.

## Key Information
- Files: ChurnAnalysis.ipynb` (code), `requirements.txt`, `README.md`,Churn Analysis ProjectReport.docx
- Results (metrics, charts) are produced when the notebook is run.
- Author: SUDHARSAN G  | Institution:PANIMALAR ENGINEERING  COLLEGE 