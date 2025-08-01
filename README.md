# TITANIC SURVIVIAL PREDICTION

#Description
This project focuses on building a predictive model to determine whether a passenger on the Titanic would have survived or not, based on features like age, gender, passenger class, fare.  Using machine learning classification techniques, this model learns patterns from the real Titanic dataset to make accurate predictions about survival outcomes.

#Objective
The goal is to analyze historical passenger data and build a model that predicts survival (Yes/No) based on key factors like:

Passenger Class (Pclass)
Gender (Sex)
Age
Siblings/Spouse aboard (SibSp)
Parents/Children aboard (Parch)
Fare paid
Embarked location

#Tools & Technologies

Python
Pandas & NumPy – for data manipulation
Matplotlib & Seaborn – for data visualization
Scikit-learn – for model building and evaluation
Jupyter Notebook – for coding and step-by-step documentation

#Machine Learning Approach

Data Cleaning:
Handled missing values (like filling missing ages with the median)
Dropped irrelevant features (like Passenger ID, Ticket, and Cabin)

Feature Encoding:
Converted categorical variables such as Sex and Embarked into numeric format

Model Training:
Trained a Logistic Regression model (also tested other models like Random Forest)

Evaluation:
Measured model performance using accuracy, confusion matrix, and classification report

Prediction:
Built a function to predict survival for new passengers based on user input
