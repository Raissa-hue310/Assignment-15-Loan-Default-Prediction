# Assignment-15-Loan-Default-Prediction
Analyze business problems, preprocess data, build machine learning models, and evaluate them for performance and fairness
This project focuses on predicting loan defaults using machine learning techniques.
The goal is to assist a financial institution in identifying high-risk borrowers so that informed decisions can be made to minimize financial losses.

The project includes:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Feature engineering

Model development using Random Forest

Model evaluation

Explainability using Permutation Feature Importance (PFI)

Fairness and ethical assessment

📂 Project Structure
Loan-Default-Prediction/
│
├── bank-loan.csv                      # Dataset used for the assignment
├── Loan_Default_Prediction.ipynb      # Notebook with full code solution
├── Assignment15_LoanDefaultReport_Short.docx   # Final report (Word format)
└── README.md                          # This file

🧠 Key Tasks Completed
✔ Task 1 – Data Analysis & Cleaning

Loaded the dataset (bank-loan.csv)

Removed missing values in the target variable (default)

Generated summary statistics and visualizations

Identified key trends such as debt-related correlations

✔ Task 2 – Feature Engineering & Scaling

Created additional predictive features:

total_debt

debt_to_income_ratio

employment_to_age_ratio

is_young_borrower

All features were scaled using StandardScaler.

✔ Task 3 – Model Training & Evaluation

Model used: Random Forest Classifier

Metrics calculated:

Accuracy

Precision

Recall

F1-score

Confusion matrix

Identified most influential features using model importance

✔ Task 4 – Explainability & Fairness

Due to SHAP library incompatibility in the environment, Permutation Feature Importance (PFI) was used for explainability.

Fairness analysis was performed on age groups:

< 35 years

≥ 35 years

No major performance disparities were detected.

✔ Task 5 – Ethical Review

Discussed:

Transparency

Bias & fairness

Privacy considerations

Importance of human oversight

Recommendations for responsible use of ML in lending

🚀 How to Run the Project

Open the notebook:
Loan_Default_Prediction.ipynb

Make sure the dataset bank-loan.csv is in the same directory.

Run all cells in order:

Data loading

EDA

Feature engineering

Model training

Explainability

Fairness analysis

The final Word report (Assignment15_LoanDefaultReport_Short.docx) summarizes all findings.

🔍 Main Findings

Debt-related variables (e.g., debt-to-income ratio, total debt) were the strongest predictors of default.

Random Forest delivered solid predictive performance.

PFI provided interpretable insight into each feature’s impact.

Fairness testing showed no major disparity across age groups, but continuous monitoring is recommended.

📄 Files Included
File	Description
bank-loan.csv	Raw dataset
Assignment15_Loan_Default_Prediction.ipynb	Full Python workflow
Assignment15_LoanDefaultReport.docx	Final written report
README.md	Project summary and instructions
🏁 Conclusion

This project demonstrates the end-to-end process of building a responsible machine learning solution for loan default prediction — from raw data analysis to model explainability and fairness evaluation.
