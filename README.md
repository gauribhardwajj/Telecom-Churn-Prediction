# Telecom-Churn-Prediction

## Overview of the project

The Telecom Churn Prediction project aims to predict which customers are likely to churn (i.e., stop using the service) based on historical data. Churn prediction is crucial in industries like telecom, where customer retention is often cheaper than acquiring new customers.

### Key steps involved in the project:
* **Data Preprocessing:** This includes handling missing values, encoding categorical variables (like customer segments), and normalizing continuous variables. By cleaning the dataset, the models can make more accurate predictions. <br>
* **Feature Selection:** The dataset contains several features like tenure, monthly charges, and customer support calls. Feature selection helps identify which attributes contribute most to customer churn. <br>
* **Model Training:** Various machine learning models, such as `Decision Trees, Random Forest, and Logistic Regression`, were trained. These models were chosen because they provide different trade-offs in terms of accuracy and interpretability.<br>
* **Evaluation Metrics:** You evaluated models using `ROC-AUC, accuracy, and precision-recall` curves to ensure the models performed well across different metrics. Random Forest provided the best results with `~80% accuracy`.<br>


### Key Features:
* Multiple Models: Trained and evaluated Decision Tree, Random Forest, and Logistic Regression. <br>
* ROC Curve Comparison: Used ROC curves to visualize and compare model performance. <br>
* Data Visualization: Plotted distributions of features like customer tenure, contract type, and churn status.<br>
* Hyperparameter Tuning: Implemented grid search to fine-tune models and improve their accuracy.<br>


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

