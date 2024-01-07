# LP2_CUSTOMER-CHURN-PROJECT
ML-driven customer churn prediction using data analysis techniques.
### **Project Description**
#### Customer Churn is the percentage of customers that stopped using a companys' product or service during a certain time frame.In business, understanding the primary cause of a customer churn can assist businesses to create a retention strategy to reduce customer churn and as such boost revenue.This project seeks to build a powerful machine learning pipeline that will estimate or predict the likelihood of a customer leaving vodafone or not.
### **Null Hypothesis**: Customers with high monthly charges do not have the tendency to churn

### **Alternate Hypothesis**:Customers with high monthly Charges have the tendency to churn
### **Analytical Questions**
#### 1.  Which payment method is the most popular?
#### 2.  Which internet service was purchased the most?
#### 3.  Which gender recorded the highest churn
#### 4.  Which one of the contract types did the highest churn
#### 5.  Which age group did the highest churn
#### 6.  Does high monthly charges affect the churn rate
##  `Data Preparation`

Data Preparation also known as **data preprocessing**, is a crucial phase in the machine learning pipeline. It involves cleaning, transforming, and structuring raw data into a format that is suitable for analysis and model building. Data preparation aims to improve the quality of the data and enhance the performance of machine learning models. This phase lays the foundation for accurate and meaningful analysis and predictions.

- **Train-test split**: Divide the data into training and testing sets for model evaluation.
- **Clean and preprocess data: Handle missing values, outliers, and inconsistencies**.
- **Data Transformation**:
    - Standardization: Scale numerical features to have a mean of 0 and a standard deviation of 1.
    - Normalization: Scale features to a specific range, typically 0 to 1.
    - Log Transformation: Apply log functions to reduce skewness in data distributions.
    - Encoding Categorical Variables: Convert categorical variables into numerical format (e.g., one-hot encoding, label encoding).
- **Feature engineering**
    - Create New Features: Generate new variables based on domain knowledge, interactions, or transformations and choose features that have the most predictive power and discard irrelevant ones.
- **Address class imbalance (if applicable)**: Over-sample, under-sample, or use class weights to balance classes.
### <b> PIPELINES
##### `These pipelines are designed to handle both numeric and categorical data in a structured and consistent way, preparing the data for machine learning models.`
# <B>EVALUATION
`Handling imbalanced dataset` 
`After running this code, X_train_resampled and y_train_resampled will contain the training data with a balanced class distribution.
## **ROC Curve Plotting**
`We are using the trained decision tree classifier to make predictions on a test set (X_test). The predicted values (rf_pred) are then compared with the true labels (y_test_encoded) to construct a confusion matrix.`
- From the curve we can see that gradient boosting classifier covered the most area with an auc of 0.88, it is the best performing model so far