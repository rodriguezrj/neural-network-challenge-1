# neural-network-challenge-1
neural-network-challenge-1


# Student Loan Repayment Prediction and Recommendation System

This project aims to predict student loan repayment success using a neural network model and provide a recommendation system for student loan options.

## Project Structure

student_loans_with_deep_learning.ipynb: Jupyter Notebook containing all the steps to preprocess data, train the model, evaluate it, and make predictions.
student_loans_model.keras: Saved Keras model for predicting student loan repayment.
README.md: Project documentation.


## Data Preprocessing

Load Data: Load the student loan dataset into a Pandas DataFrame.
Define Features and Target:
Features (X): All columns except credit_ranking.
Target (y): The credit_ranking column.
Split Data: Split the data into training and testing sets.
Scale Data: Use StandardScaler to scale the features.

## Model Building and Training

Define the Model: Create a Sequential model with two hidden layers and one output layer.
Compile the Model: Use the Adam optimizer and binary cross-entropy loss function.
Train the Model: Fit the model on the training data for 50 epochs.

## Model Evaluation
Evaluate the Model: Calculate loss and accuracy on the test data.
Make Predictions: Use the trained model to make predictions on the test data.
Classification Report: Print a classification report to evaluate the predictions.

## Saving and Loading the Model
Save the Model: Save the trained model to a .keras file.
Load the Model: Load the saved model from the .keras file.

## Prediction and Analysis
Make Predictions: Predict loan repayment success using the loaded model.
Save Predictions: Save the predictions to a DataFrame and convert probabilities to binary results.
Display Predictions: Display a sample of the predictions.

## Recommendation System

### Data Needed

Student Financial Data: Income, employment status, credit history, and existing debts.
Student Academic Data: Field of study, academic performance, and educational institution.
Loan Details: Terms like interest rates, amounts, and provider information.
Historical and Feedback Data: Repayment success rates and student feedback on loans.

## Filtering Method

Content-Based Filtering: Matches loan options to individual students using detailed attributes of their financial and academic profiles.


## Real-World Challenges

Privacy and Data Security: Ensuring robust security measures to protect sensitive financial and personal data.
Bias and Fairness: Avoiding bias to ensure fair recommendations for all students.

## Contributor
Robert Rodriguez