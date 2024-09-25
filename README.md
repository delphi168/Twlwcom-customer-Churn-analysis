# Telecom-customer-Churn-analysis

# Project Overview
This project aims to predict customer churn in a telecom company using various customer attributes like tenure, monthly charges, contract types, and more. By accurately predicting customers who are likely to churn, the company can target retention strategies effectively.

# Dataset
The dataset consists of 1,000 samples with the following features:

CustomerID: Unique identifier for each customer.
Age: Age of the customer.
Tenure: Number of months the customer has been with the company.
MonthlyCharges: The amount the customer pays per month.
TotalCharges: The total amount the customer has paid.
Gender: The customer’s gender.
ContractType: Type of contract (e.g., month-to-month, one-year, two-year).
InternetService: Type of internet service (e.g., Fiber optic, DSL).
TechSupport: Whether the customer has tech support.
Churn: Whether the customer churned (target variable).
Goals
Build a predictive model to identify customers likely to churn.
Perform feature importance analysis to identify factors influencing churn.
Provide customer segmentation for targeted retention strategies.
Tools and Techniques
Exploratory Data Analysis (EDA) to uncover trends and relationships.
Logistic Regression and Random Forest models for churn prediction.
GridSearchCV for hyperparameter tuning on SVC.
SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance.
Random Forest for feature importance.
KMeans Clustering for customer segmentation.
Elbow Method for determining optimal K in clustering.
Key Metrics
Since the dataset is imbalanced (more churned than not churned), the key metrics are:

Recall: Focused on capturing all customers likely to churn.
F1 Score: Balance between precision and recall.
Accuracy: Overall prediction performance.
Results
Logistic Regression: (Recall: 0.9774, Accuracy: 0.92, F1 Score: 0.9558)
SVC (after GridSearch): (Recall: 0.9718, Accuracy: 0.97, F1 Score: 0.9829)
Random Forest: (Recall: 0.9944, Accuracy: 0.995, F1 Score: 0.9972)
Customer Segmentation
Using KMeans clustering, customers were segmented based on their features like monthly charges, tenure, and contract type. Segmentation helps in understanding customer groups better for targeted retention strategies.

# Conclusion
This project helps telecom companies identify churn drivers, accurately predict churn, and segment customers for better retention strategies.
