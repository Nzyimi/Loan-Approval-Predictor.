1. Project Overview
This project is part of a group assignment aimed at building a machine learning model to predict whether a loan application should be approved based on applicant information. The project follows the complete ML lifecycle — from data loading, cleaning, and exploratory analysis, to model training, evaluation, and testing.

2. Project Goal
To predict loan approval using binary classification (Approved = Y, Not Approved = N) and assist financial institutions in making data-driven lending decisions.

3. Dataset
•	Name: Loan Approval Dataset
•	Source: Kaggle – Loan Approval Data Set
•	File Used: Loan_Train.csv
•	Description: Contains applicant demographic, financial, and loan-related features.

4. Methodology
The steps followed in the project:
1.	Understanding the Problem & Objectives – Defined prediction goals, target variable, and success metrics.
2.	Data Loading – Imported dataset into Jupyter Notebook.
3.	Exploratory Data Analysis (EDA) – Checked data types, missing values, distributions, and target class balance.
4.	Data Cleaning & Preprocessing – Handled missing values, label encoded categorical variables, and scaled numerical features.
5.	Feature Selection – Used correlation analysis and dropped irrelevant columns like Loan_ID.
6.	Data Splitting – Train-test split (80%-20%).
7.	Model Training – Implemented Logistic Regression and Decision Tree Classifier.
8.	Model Evaluation – Compared models using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
9.	Testing – Evaluated models on unseen test data.
10.	Conclusion & Recommendations – Summarized performance and gave recommendations.

5. Tech Stack
•	Language: Python
•	Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
•	Environment: Jupyter Notebook

6. Results
•	Best Model: whether Logistic Regression or Decision Tree performed better
•	Performance Metrics: Accuracy, Precision, Recall, F1-score reported in the notebook and report.
•	Insights: Key predictors for loan approval identified include Credit History, Applicant Income, and Loan Amount.



7. How to Run the Project
1.	Clone the repository:
bash
git clone <repo-link>
cd loan-approval-predictor
2.	Install dependencies:
bash
pip install -r requirements.txt
3.	Open the notebook:
bash
CopyEdit
jupyter notebook Group-5.ipynb
4.	Run cells in sequence.

9. Contributors
•	Bernice Eunice
•	Erick Mutinda
•	Glorias Mwikali
•	Nathan Muoki
•	Joy  Wangari 

