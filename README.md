# Bank Customer Churn Prediction

# 1. Project Overview
Customer churn refers to customers discontinuing a company's service. Customer retention is crucial because acquiring new customers is often more expensive than retaining existing ones.
This project uses Machine Learning techniques to predict whether a customer is likely to churn based on customer demographics, account information, and service usage patterns.

# 2. Problem Statement
The objective of this project is to build a classification model that can predict customer churn and help businesses identify customers who are at risk of leaving.

# 3. Dataset Information
i. Features Used
ii. CreditScore
iii. Geography
iv. Gender
v. Age
vi. Tenure
vii. Balance
viii. NumOfProducts
ix. HasCrCard
x. IsActiveMember
xi. EstimatedSalary
# Target Variable
Exited
0 → Customer stays
1 → Customer churns

# 4. Technologies Used
i. Python
ii. Pandas
iii. NumPy
iv. Matplotlib
v. Seaborn
vi. Scikit-Learn

# 5. Machine Learning Workflow
## Data Preprocessing
Removed unnecessary columns
Handled categorical variables
Feature scaling
# Exploratory Data Analysis (EDA)
Churn distribution analysis
Correlation analysis
Feature importance analysis
# Model Building
Logistic Regression
Random Forest Classifier
# Model Evaluation
Accuracy Score
Confusion Matrix
Precision
Recall
F1-Score

# 6. Visualizations Included
## Customer Churn Distribution
Shows the proportion of customers who stayed and churned.
<img width="549" height="391" alt="image" src="https://github.com/user-attachments/assets/e997b17c-a261-4939-a33b-7c4ecafff6d3" />
## Correlation Heatmap
Displays relationships among features.
<img width="1042" height="813" alt="image" src="https://github.com/user-attachments/assets/d4b1f850-2962-43d0-82a1-faf35d129dfd" />
## Feature Importance Graph
Identifies the most influential factors affecting customer churn.
<img width="982" height="545" alt="image" src="https://github.com/user-attachments/assets/57e6fe6a-cf8b-4d54-bf6d-47bd0190ea1d" />

# 7. Results
Logistic Regression - 81.1%
Random Forest - 86.65%

# 8. Conclusion
This project successfully predicts customer churn using Machine Learning techniques. The model helps businesses identify at-risk customers and develop retention strategies, ultimately reducing customer loss and improving profitability.
