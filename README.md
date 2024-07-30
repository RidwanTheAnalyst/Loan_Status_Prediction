Loan Approval Prediction

This repository contains a machine learning project aimed at predicting loan approval status based on various applicant details. The project involves data cleaning, exploratory data analysis (EDA), and training a Support Vector Machine (SVM) model to make predictions.

Table of Contents

Project Overview
Data Collection and Processing
Data Visualization
Model Training and Evaluation
Results
How to Use
Contributing
License
Project Overview

The objective of this project is to predict whether a loan will be approved or not based on various attributes such as applicant's income, loan amount, credit score, etc. The dataset used in this project is a hypothetical loan dataset.

Data Collection and Processing

The dataset used in this project contains information about:

Loan ID
Gender
Marital Status
Dependants
Education
Self Employment Status
Applicant Income
Coapplicant Income
Loan Amount
Loan Amount Term
Credit Score
Property Area
Loan Status (Target variable)
Steps:
Load the dataset using Pandas.
Verify and clean the data by handling missing values.
Perform label encoding for categorical variables.
Split the data into features (X) and target (Y).
Data Visualization

To understand the distribution and relationships within the data, various visualizations are performed:

Pie chart to show the percentage of approved and disapproved loans.
Count plots to show the impact of education, gender, and marital status on loan approval.
Model Training and Evaluation

The machine learning model used for this project is a Support Vector Machine (SVM) with a linear kernel. The steps include:

Splitting the data into training and testing sets.
Training the SVM model on the training set.
Evaluating the model's performance on both the training and testing sets.
Results

The accuracy of the model on the training data is approximately 70.27% and on the testing data is approximately 70.24%.

How to Use

Clone the repository:
bash
Copy code
Navigate to the project directory:
bash
Copy code
cd loan-approval-prediction
Install the required libraries:
Copy code
pip install -r requirements.txt
Run the notebook or script:
Copy code
jupyter notebook
or
Copy code
python loan_approval_prediction.py
Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes.

License

This project is licensed under the MIT License.

Contact

Name: Ridwan Asaolu
LinkedIn: Ridwan Asaolu
GitHub: RidwanTheAnalyst
X (formerly Twitter): arsharvin
