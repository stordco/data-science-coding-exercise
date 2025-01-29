# data-science-coding-exercise
Data Scientist Coding Exercise

## Preparation of the Assessment Environment
- All coding exercises have been verified using Google Colab https://colab.research.google.com/
- It is suggested that you as well use Google Colab but please feel free to use whatever platform or coding environment you feel most comfortable with.
- Ensure that your coding platform (e.g., Google Colab) is set up and fully functional.
- Confirm that the development environment has the necessary libraries pre-installed (e.g., Python, pandas, scikit-learn, Jupyter Notebook).
- The 3 CSV files are included in this repository will be needed for this exercise.
- Once completed, please share your colab notebook and outputs or zip up the code and outputs. Email it to the Stord talent acquisition team member you have been working with.

## Statistical Inference
**Model Building and Evaluation**
- You are provided with a dataset from a marketing campaign. The dataset includes user_id, age, income, previous_purchases, and purchase (1 if the user made a purchase, 0 otherwise).
- Your task is to build a logistic regression model to predict whether a user will make a purchase based on the provided features.

**Instructions**
1. Load the dataset.
2. Split the dataset into training and testing sets.
3. Train a logistic regression model on the training set.
4. Evaluate the model on the testing set using accuracy, precision, recall, and F1 score.
5. Output the evaluation metrics.

**Expected Output**
Accuracy, precision, recall, and F1 score

**Dataset**

https://github.com/stordco/data-science-coding-exercise/blob/e8ee79cec4067fef8a32ba7aeb9c4ea17087a8a5/marketing_campaign-stat-inf-q3-hard.csv

## General Programming

**Model Building and Data Analysis**
- You are given a dataset of customer transactions in a CSV file.
- The dataset includes transaction_id, customer_id, transaction_amount, and transaction_date.
- Your task is to write a function that reads the dataset and returns the total transaction amount for each customer.

**Instructions**
1. Write a function named total_transaction_amount_per_customer.
2. The function should take a file path as input.
3. Read the CSV file into a pandas DataFrame.
4. Group the data by customer_id and calculate the total transaction amount for each customer.
5. Return a dictionary where the keys are customer_id and the values are the total transaction amounts.

**Expected Output**
A dictionary with customer IDs and their corresponding total transaction amounts.

**Dataset**

https://github.com/stordco/data-science-coding-exercise/blob/54f77ac0e37b1e4f7ce46bc66397ce0b7dad8c3f/customer_transactions_small.csv

## Predictive Analytics

**Model Building and Hyperparameter Tuning**
- You are given a dataset containing customer churn information for a telecommunications company.
- The dataset includes customer_id, tenure, monthly_charges, total_charges, contract_type, and churn (1 if the customer churned, 0 otherwise).
- Your task is to build a logistic regression model to predict customer churn and perform hyperparameter tuning using cross-validation.

**Instructions**
1. Load the dataset.
2. Perform any necessary data cleaning and feature engineering.
3. Split the dataset into training and testing sets.
4. Train a logistic regression model and use cross-validation to find the best hyperparameters.
5. Evaluate the final model on the testing set using accuracy, precision, recall, and F1 score.

**Expected Output**
Accuracy, precision, recall, and F1 score for the test set

**Dataset**

https://github.com/stordco/data-science-coding-exercise/blob/9ec469ef3f73609f7d0923d9ac8e234863e482f8/customer_churn-predict-model-q3-hard.csv


