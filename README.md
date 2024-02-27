# Data Science Projects

Welcome to my Data Science Projects Repository! This repository contains a collection of my data science projects, showcasing my skills and expertise in the field. Each project demonstrates different aspects of data analysis, machine learning, and visualization.

## Projects

### 1. Sleep Disorder Prediction

- **Description:** The project aims to predict sleep disorders and their types by analyzing lifestyle and medical variables, such as age, BMI, sleep duration, blood pressure, and more. Compare the model accuracy between Decision Tree Clasifier vs Random Forest Classifier
- **Technologies Used:** Random Forest Classifier and Decision Tree classifier
- **Results:** The Random Forest Classifier performed well with an accuracy of 89%.

### 2. Titanic Survival Prediction

- **Description:** The project aims to predict survival of titanic passenger based on their Age, Gender and others and compare the various prediction model accuracy.
- **Technologies Used:** Naive Bayes vs Decision Tree classifier vs Random Forest Classifier vs Neural Network
- **Results:** The Random Forest Classifier performed well with an accuracy of 89%.

### 3. House Price Prediction

- **Description:** The project predicts the house price after studying the variables such as location, area, bredroom, bathroom count and many more.
- **Technologies Used:** The notebooks uses Linear Regression, Ridge Regression and Random Forest Regressor. Model training was done using pipeline.
- **Results:** The Random Forest Regressor performed best with accuracy of 87.89%

### 4. Customer Churn Prediction

- **Description:** The main objective of the Bank Customer Churn Prediction project is to analyze the demographics in order to predict whether a customer will leave the bank or not.
- **Technologies Used:**

* Features with outliers has been handled using IQR method.
* Imbalance dataset has been handled using SMOTE method.
* The dataset was trained with 7 different model Logistic Regression, SVM, KNN, Decision Tree Classifier, Random Forest Classifier, XGboost and Catboost. Tree based model training was done using GridSearchCV to find the best parameters.

- **Results:** Since this case is a imbalance dataset classification problem, we have to evaluate the f1-score, specificity, precision-recall curves and precision (FP cost more than FN).XGBoost model performed best with highest value of accuracy, precision, f1-score, specificity, precision-recall curves compare to other models. Catboost perform the 2nd best.

### 5. Heart Stroke Prediction

- **Description:** The project predicts the risk of heart stroke on studying the person's demographics and medical info
- **Technologies Used:** The notebooks uses Logistic Regression, Support Vector Machine, Decision Tree Classifier and KNN. Decision Tree Model training was done using GridSearchCV to find the best parameters.
- **Results:** The logistic regression, SVM and KNN performs the best with 94% accuracy. Decision Tree Model can achieve the same accuracy provided training using GridSearchCV method.

### 6. Programming Job Application Prediction

- **Description:** The project predicts the employement score for progamming job application based on hiring survey data.
- **Technologies Used:** The notebooks uses Decision Tree Classifier, Support Vector Machine, KNN, Random Forest Classifier and XGboost. Decision Tree Model, RFC and XGBoost training was done using GridSearchCV to find the best parameters.
- **Results:** The Xgboost, RFC and SVM performs the best with ~78% accuracy. Bining for "PreviousSalary" perform better with higher accuracy.

### 7. Warranty Claims Fraud Prediction

- **Description:** The project predicts the fraudulent claims prediction from total warranty claims of television product
- **Technologies Used:** The notebooks uses Decision Tree Classifier, Random Forest Classifier, logistic regression and XGboost. Decision Tree Model, RFC and XGBoost training was done using GridSearchCV to find the best parameters.
- **Results:** I have used Decision Tree Classifier, Random Forest Classifier, Logistic Regression and Xgboost Classifier. All these models gave excellent accuracy of 90-92%. However, due to lesser number of fraudulent claims or small dataset size (323 Not Fraud, 35 Fraud), the models have poor recall score for fraudulent claims. But this issue can be resolved by collecting more data.

### 8. Credit Card Fraud Prediction

- **Description:** It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase

- **Technologies Used:**

* Features with outliers has been handled using log transformation & IQR method.
* Imbalance dataset has been handled using SMOTE, undersampling and mix method.
* The dataset was trained with 6 different model Logistic Regression, Naive Bayes,Decision Tree Classifier, Random Forest Classifier, XGboost & Catboost. Tree based model training was done using GridSearchCV to find the best parameters.

- **Results:** Since this case is a imbalance dataset classification problem, I will have to evaluate the f1-score, specificity, precision-recall curves and precision (FP cost more than FN).XGBoost model performed best with highest value of accuracy, precision, f1-score, specificity, precision-recall curves compare to other models. Catboost perform the 2nd best.
