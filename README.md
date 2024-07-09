# Customer-churn-prediction
To Build a Machine Learning Model that will Predict Telco Customer Churn

Overview
This project aims to predict customer churn of telco company using machine learning techniques. The goal is to identify customers who are likely to leave the company and understand the key factors driving their decisions, enabling the company to take proactive measures to retain customers.

Table of Contents

Business Understanding
Data Understanding
Data Preparation
Evaluation
Conclusion


**Business Understanding:** At the Stage of Business Understanding I define the problem statement of the project, define the objective, I also define the Key Metrics and Success Criteria, and procced to give explanation of each column in the dataset, develope my Null and Alteenate hypothesis as well as state the Analytical Question to be Answered.

**Data Understanding** I started the Data Understanding stage by importing all the necessary libraries Create a connection by accessing the connection string with the environment variables and get the first dataset from the database then download the second data from GitHub repository and laod to daframe, I move on to concatenate the two datasets, and proceed to do exploratory data analysis which include (Multi-variate, Bi-variate and Univariate analyses), then do the Hypothesis test and also anwered all the Analytical Questions.

**Data Preparation** this stage includes Putting all the preprocessing steps into a ColumnTransformersteps, and create a pipeline that includes the preprocessor and a classifier, fit the pipeline to the training data, redict on the test set and evaluate the module results, Several machine learning models were tested to predict customer churn, including: Random Forests, k-NN classifier, Decision Tree Pipeline, Gradient Boosting Classifier Pipeline.

**Evaluation** The performance of the models was evaluated using the following metrics:

Accuracy
Precision
Recall
F1-Score
ROC-AUC
The final model was selected based on its performance on these metrics, with a particular focus on recall to minimize false negatives.

**Hyperparameter Tuning** Hyperparameter tuning was performed using GridSearchCV on the select best Model.

**Model Testing** Test the model using the test data.

**Business Impact Assessment and Documentation of the Model** Writing the Business Impact Assessment and Documentation of the Model.

**Conclusion**
The project successfully identified key factors influencing customer churn and developed a predictive model with high accuracy and recall. The insights gained can help the telec company implement targeted retention strategies to reduce churn.


![alt text](<Screenshot 2024-07-07 080126.png>)

