Bank Customer Churn Prediction 📊

This project utilizes machine learning techniques to predict the likelihood of bank customers leaving the bank (churning). By identifying at-risk customers, banks can implement proactive retention strategies.

🚀 Project Overview
Customer churn is a critical metric for financial institutions. This project focuses on analyzing customer demographics and banking behavior to build a classification model that predicts the Exited status of a customer.

📁 Dataset
The project uses the Churn_Modelling.csv dataset, which contains 10,000 records of bank customers with the following key features:

CreditScore: Customer's creditworthiness.

Geography: Country of residence (France, Spain, Germany).

Gender: Male or Female.

Age: Age of the customer.

Tenure: Number of years the customer has been with the bank.

Balance: Account balance.

NumOfProducts: Number of bank products used.

HasCrCard: Whether the customer has a credit card (1 = Yes, 0 = No).

IsActiveMember: Whether the customer is an active member (1 = Yes, 0 = No).

EstimatedSalary: Customer's annual salary.

Exited: Target variable (1 = Churned, 0 = Retained).

🛠️ Data Preprocessing
The notebook includes several critical preprocessing steps to prepare the data for modeling:

Feature Dropping: Removed irrelevant columns such as RowNumber, CustomerId, and Surname to reduce noise.

Handling Categorical Data: Converted Geography and Gender into numerical format using One-Hot Encoding (pd.get_dummies) with drop_first=True to avoid the dummy variable trap.

Data Exploration: Visualized customer tenure distribution using histograms to compare churned vs. retained customers.

📊 Visualizations
The analysis includes a visualization titled "Bank Customer Prediction", which shows the relationship between customer Tenure and the number of customers, categorized by their churn status (Exited = 0 vs Exited = 1).

💻 Tech Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib,TensorFlow

Environment: Jupyter Notebook

📝 How to Use
Ensure you have the dataset Churn_Modelling.csv in the same directory as the notebook.

Install the required dependencies:

Bash
pip install pandas numpy matplotlib
Run the cells in bank customer churn prediction.ipynb to see the data analysis and preprocessing workflow.
