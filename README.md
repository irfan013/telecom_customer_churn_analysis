# Implementing Machine learning to telecom customer churn dataset

Dataset source: https://learn.datacamp.com/courses/marketing-analytics-predicting-customer-churn-in-python

## Descriptions of the dataset
### Dependent variable
- Churn: Churn status of the customer (yes; no)

### Independent variables (features)

- Account_Length: Length of availing the service from this telecom
- Vmail_Message: Number of Voice mail message sent
- Day_Mins: Number of mintues talked during day time
- Eve_Mins: Number of mintues talked during evening time
- Night_Mins: Number of mintues talked during night time
- Intl_Mins: Number of mintues talked internationally
- CustServ_Calls: Number of times called at Customer Care for services
- Intl_Plan: Availing International plan or not (yes; no)
- Vmail_Plan: Availing Voice mail plan or not (yes; no)
- Day_Calls: Number of calls during day time
- Day_Charge: Total bills for day time calls
- Eve_Calls: Number of calls during evening time
- Eve_Charge: Total bills for evening time calls
- Night_Calls: Number of calls during night time
- Night_Charge: Total bills for night time calls
- Intl_Calls: Number of international calls
- Intl_Charge: Total bills for international calls
- State: US State name of the customer (51 Values: AK=Alaska, AL=Alabama,...,WY=Wyoming)
- Area_Code: US Area code of the customer (3 Values: 415, 510, 408)
- Phone: Phone number of the customer (3333 unique values each has 7 numeric digits with a hyphen after 3rd digit from left)

### Analysis performed (Classification tree)
 - Importing the dataset
 - Explaining the features and target variable
 - Performing appropriate data preprocessing including Label or One-hot Encoding
 - Perform Data Transformation (StandardScaler or MinMaxScaler)
 - Spliting the original dataset into the train set (80%) and the test set (20%) with addition of random state and stratification
 - Performing the training with Decision Tree Classifier
 - Producing a tree diagram of the Decision Tree
 - Perform Grid Search and Cross-Validation
 - Finding the Confusion Matrix, Classification report, and ROC-AUC
 - Finding accuracy, precision, recall, f1 score

Update: 23 October 2021
