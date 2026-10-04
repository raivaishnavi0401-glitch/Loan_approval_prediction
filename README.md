# Loan Approval Prediction using Python

## Project Overview

This project uses Python and Machine Learning to predict whether a loan application will be approved or rejected. It uses Logistic Regression to make predictions based on applicant details such as income, loan amount, CIBIL score, education, and assets.

## Objectives

* Analyze loan application data.
* Clean and prepare the dataset.
* Apply Machine Learning using Logistic Regression.
* Predict loan approval or rejection.
* Evaluate the model's performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## Dataset Features

The project uses the following applicant details:

* Number of Dependents
* Education
* Self-Employed Status
* Annual Income
* Loan Amount
* Loan Term
* CIBIL Score
* Residential Assets Value
* Commercial Assets Value

**Target Variable:** Loan Status (Approved or Rejected)

## Project Workflow

1. Import the required Python libraries.
2. Load and explore the dataset.
3. Check missing values and clean column names.
4. Convert categorical data into numerical values.
5. Select input features and the target variable.
6. Split the data into training and testing sets.
7. Apply feature scaling using StandardScaler.
8. Train the Logistic Regression model.
9. Predict loan status and approval probabilities.
10. Evaluate the model using accuracy, confusion matrix, and classification report.
11. Predict the loan status of a new applicant.

## Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a classification algorithm used to predict outcomes such as approved or rejected. In this project, it predicts loan status based on the applicant's financial and personal details.

## Model Evaluation

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

## Results

The trained model predicts whether a loan application is likely to be approved or rejected. It also calculates the approval probability for each applicant.

## How to Run the Project

1. Download or clone this repository.
2. Download the loan dataset and upload it to Google Colab.
3. Open the Jupyter Notebook.
4. Update the dataset file path if required.
5. Run all cells in the notebook.

## Future Improvements

* Test additional Machine Learning algorithms.
* Improve model performance through hyperparameter tuning.
* Create an interactive dashboard for loan predictions.
* Deploy the model as a web application.

## Conclusion

This project demonstrates how Python and Logistic Regression can be used to predict loan approval outcomes by analyzing applicant data and evaluating a Machine Learning model.

**Note:** This project is for educational purposes. Predictions are not a substitute for actual financial institution lending decisions.
