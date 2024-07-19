# Telecom-Churn-Prediction

## What is Churn Rate?

Customer churn is the percentage of customers that stopped using your company’s product or service during a certain time frame.

Churn rate is a key indicator of customer satisfaction:
- A low churn rate signifies satisfied customers.
- A high churn rate indicates that customers are leaving.

Churn serves as a valuable measure of growth potential. It tracks the customers you lose, while growth rates track the new customers you gain. Analyzing these metrics together reveals your business's overall growth:
- If your growth rate exceeds your churn rate, your business is expanding.
- Conversely, if churn surpasses growth, your business is contracting.

# FINAL ACCURACY PERCENTAGE

### 1. Decision Tree
Before Hyperparameter Tuning - 72.4 %
After Hyperparameter Tuning - 77.4 %

### 2. Random Forest
Before Hyperparameter Tuning - 80.3 %
After Hyperparameter Tuning - 80.5 %

### 1. Decision Tree
Before Hyperparameter Tuning - 80.28 %
After Hyperparameter Tuning - 80.48 %

[For more details and understanding click here!](Documentation.pdf)

## Data Preprocessing Steps:
- Convert data types of variable that are misclassified.
- Remove Duplicate Records
- Remove Unique Value Variables
- Remove Zero Variance Variables
- Outlier Treatment : 1) Boxplot- Q3(1.5* IQR) & Q1- (1.5*IQR)
                      2) Standardization- +/- 3 Sigma Approach
                      3) Capping & Flooring
- Missing Value Treatment : 1) Remove records if NA's are less than 5%
                            2) Remove if NA's are 50% in any variable
                            3) Impute with Mean/Mode
- Removing highly correlated variables
- Removing Multicollinearity (VIF>5)

