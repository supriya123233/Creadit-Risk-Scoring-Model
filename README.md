💳 Credit Risk Scoring Model

An end-to-end Machine Learning project that predicts whether a loan applicant is High Risk (Default) or Low Risk (Safe) using financial and personal features.

🚀 Project Overview

Financial institutions face challenges in assessing credit risk for loan applicants. This project uses a Random Forest Classifier to predict credit default likelihood based on applicant information such as income, loan amount, credit history, and more.

I built an end-to-end ML pipeline covering data preprocessing, feature engineering, model training, evaluation, and deployment using Streamlit.

🧩 Tech Stack

Python 3.x

Pandas, NumPy – Data manipulation & preprocessing

Scikit-learn – Machine Learning model building

Streamlit – Web app interface

Pickle – Model serialization

⚙️ Project Workflow

Data Preprocessing

Handling missing values

Encoding categorical features

Feature scaling using StandardScaler

Model Building

Trained a Random Forest Classifier

Tuned hyperparameters using cross-validation

Evaluated model with accuracy, precision, recall, and ROC-AUC

Model Deployment (Local)

Serialized model, encoder, and scaler using pickle

Built an interactive Streamlit app to simulate credit risk scoring

📊 Input Features
Feature	Description
person_age	Applicant's age
person_income	Annual income
person_home_ownership	Type of home ownership
person_emp_length	Employment length (in months)
loan_intent	Purpose of the loan
loan_grade	Loan grade assigned
loan_amnt	Loan amount
loan_int_rate	Interest rate on the loan
loan_percent_income	Loan as a percentage of income
cb_person_default_on_file	Whether applicant has defaulted before
cb_person_cred_hist_length	Credit history length (in years)
🧠 Model Performance
Metric	Score
Accuracy	0.87
Precision	0.84
Recall	0.81
ROC-AUC	0.90

(Values are illustrative — update with your actual metrics.)
