# CODSOFT_TASK1

## Titanic Survival Prediction

### CODSOFT Data Science Internship - Task 1

## Project Overview

This project focuses on predicting whether a passenger survived the Titanic disaster using Machine Learning.

The Titanic dataset contains information about passengers such as age, gender, passenger class, fare, and other related features.

## Objective

The objective of this project is to build a Machine Learning classification model that predicts whether a passenger survived or did not survive.

## Dataset

The dataset used in this project is the Titanic dataset.

Important features include:

- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Fare
- Port of Embarkation (Embarked)
- Survival Status (Survived)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow

1. Import Python libraries
2. Load the Titanic dataset
3. Explore the dataset
4. Analyze missing values
5. Perform Exploratory Data Analysis (EDA)
6. Clean and preprocess the data
7. Convert categorical data into numerical values
8. Split the dataset into training and testing sets
9. Train a Logistic Regression model
10. Make predictions
11. Evaluate the model using accuracy and confusion matrix

## Data Preprocessing

The following preprocessing steps were performed:

- Missing Age values were replaced with the median age.
- Missing Embarked values were replaced with the most frequent value.
- The Cabin column was removed because it contained many missing values.
- PassengerId, Name, and Ticket columns were removed.
- Categorical columns were converted into numerical values using Label Encoding.

## Machine Learning Model

### Logistic Regression

Logistic Regression was used as the classification algorithm to predict the survival status of passengers.

## Model Evaluation

The model was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The model achieved approximately **81% accuracy** on the test dataset.

## Conclusion

This project demonstrates a complete Machine Learning workflow, starting from data exploration and preprocessing to model training, prediction, and evaluation.

The Logistic Regression model was able to predict Titanic passenger survival with approximately 81% accuracy on the test data.

## Files

- `CODSOFT_Task1_Titanic_Survival_Prediction.ipynb` - Jupyter/Google Colab notebook containing the complete project.
- `Titanic-Dataset (1).csv` - Dataset used for the project.
