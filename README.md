## Credit Card Customer Churn Prediction

#### Introduction
This project aims to predict customer churn in a credit card business. The dataset used for analysis contains 10,000 observations with 21 variables. The main focus is to identify the top features that accurately predict customer churn based on exploratory analysis and modeling techniques.

#### Data Sources and Characteristics
The data was obtained from Kaggle and consists of 10,000 observations with 21 variables. After performing exploratory data analysis (EDA), the following variables were identified as the top three important features for predicting customer churn:

Total_Relationship_Count: Total number of products held by the customer.
Months_Inactive_12_mon: Number of months inactive in the last 12 months.
Total_Revolving_Bal: Total Revolving Balance on the Credit Card.

#### Data Cleaning and Preprocessing
EDA was performed to visualize and understand the relationships between variables. The dataset was checked for missing values, duplicates, and outliers. The data was found to be imbalanced, with 20% attrited customers and 80% existing customers. To address this imbalance, oversampling techniques were used.

#### Reduce Dimension
To reduce the dimensionality of the dataset, correlation plots were analyzed, and regression analysis was performed to identify the most important variables for predicting customer churn.

#### Partition of Data
The dataset was partitioned into 60% training data and 40% validation data. Multicollinearity tests were conducted to handle highly correlated variables.

#### Methodologies
Several modeling techniques were employed to predict customer churn:

Logistic Regression
Stepwise Regression
Random Forest
Decision Trees
Naive Bayes
Empirical Results
Random Forest outperformed other models, providing the highest accuracy in predicting customer churn. The top 8 important features for predicting attrition were identified, including Customer Age, Total Relationship Count, Months Inactive 12 months, Total Revolving Bal, Total Amt Change Q4-Q1, Total Trans Amt, Total Trans Ct, and Total Ct Change Q4-Q1.

#### Conclusion
The project successfully predicted customer churn in the credit card business. Random Forest performed the best among the models tested, providing valuable insights into the most critical factors influencing customer attrition.

#### Recommendations
Based on the findings, the following recommendations are suggested:

Provide incentives to customers with decreased transaction counts compared to the previous quarter.
Develop targeted marketing strategies for customers with blue cards.
Focus on engaging customers who have not used their cards for more than 2 months.
Target customers with income less than 40K and a graduate degree for specific marketing campaigns.
For more details and in-depth analysis, please refer to the project report and the appendix section containing visualizations.
