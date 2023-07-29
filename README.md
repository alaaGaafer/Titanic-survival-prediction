# Titanic-survival-prediction
This project aims to predict the survival of passengers on the Titanic using machine learning techniques.

## Introduction

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, resulting in the deaths of more than 1500 passengers and crew.

In this project, we will use the Titanic dataset to build a predictive model that can predict whether a passenger survived or not based on various features such as age, sex, class, and more.

## Dataset

The dataset used in this project is the famous Titanic dataset available on Kaggle. The dataset contains information about each passenger, including features such as:

- PassengerId: Unique identifier for each passenger
- Survived: Whether the passenger survived (0 = No, 1 = Yes)
- Pclass: Ticket class (1 = 1st class, 2 = 2nd class, 3 = 3rd class)
- Name: Name of the passenger
- Sex: Gender of the passenger
- Age: Age of the passenger
- SibSp: Number of siblings/spouses aboard
- Parch: Number of parents/children aboard
- Ticket: Ticket number
- Fare: Fare paid for the ticket
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Data Preprocessing

Before building the model, we performed some data preprocessing steps, which include:

- Handling missing values: We replaced missing values in the Age column with the median value. We also dropped the Cabin column as it had a large number of missing values.
- Feature engineering: We created a new feature called "Age Category" by categorizing the age column into different age groups (children, youth, young adults, middle-aged adults, and senior citizens).

## Exploratory Data Analysis (EDA)

We performed exploratory data analysis to gain insights from the data and understand the relationships between different features and the target variable (Survived). We created various visualizations, such as bar plots and box plots, to analyze the data.

## Model Building

We used two machine learning models for prediction: Logistic Regression and Support Vector Machine (SVM). We split the training data into training and testing sets, trained the models on the training set, and evaluated their performance on the testing set.

## Results

The results of the model evaluation are as follows:

### Logistic Regression Model:
- Accuracy: 80.36%
- Classification Report:
  - Precision, Recall, and F1-score for each class (Survived = 0 and Survived = 1)
- Confusion Matrix:
  - True Positive (TP), True Negative (TN), False Positive (FP), and False Negative (FN) values

### Support Vector Machine (SVM) Model:
- Accuracy: 80.36%
- Classification Report:
  - Precision, Recall, and F1-score for each class (Survived = 0 and Survived = 1)
- Confusion Matrix:
  - True Positive (TP), True Negative (TN), False Positive (FP), and False Negative (FN) values

## Conclusion

In this project, we successfully built machine learning models to predict the survival of passengers on the Titanic. The Logistic Regression and SVM models achieved similar accuracy, and their performance can be further improved with hyperparameter tuning and feature engineering.

Feel free to explore the Jupyter Notebook for more details on the data analysis, model building, and evaluation.

If you have any questions or suggestions, please feel free to reach out!

## Acknowledgments

Special thanks to Kaggle for providing the Titanic dataset and the Titanic dataset contributors for collecting and sharing the data.
