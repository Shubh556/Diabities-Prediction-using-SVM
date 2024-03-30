# Diabetes Prediction Model

This project aims to predict whether a person has diabetes or not based on certain health-related features. The model is built using machine learning techniques and utilizes a dataset containing information about individuals, including factors like their glucose level, blood pressure, and age.

## Data Preprocessing

Before training the model, the data is preprocessed in the following steps:

1.Data Cleaning: Check for and handle any missing or erroneous values.

2.Data Standardization: Scale the features to have a mean of 0 and a standard deviation of 1. This ensures that all features contribute equally to the model.

## Model Building

The model is built using Support Vector Machine (SVM), a supervised learning algorithm. SVM is chosen for its ability to handle high-dimensional data and its effectiveness in classification tasks.

## Model Evaluation

The performance of the model is evaluated using accuracy, which measures the percentage of correctly predicted instances out of all instances.

1.Training Accuracy: The accuracy of the model on the training data.
2.Test Accuracy: The accuracy of the model on unseen test data.

## Testing the Model

Once the model is trained and evaluated, it can be used to predict whether a new individual is diabetic or not based on their health information. The model takes the individual's data, standardizes it, and then predicts the outcome.