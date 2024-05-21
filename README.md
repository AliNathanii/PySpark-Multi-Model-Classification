# PySpark-Multi-Model-Classification
This project demonstrates the use of PySpark for building and evaluating multiple classification models on a multivariate dataset. Our models will predict whether the patient can donate their blood or not (either positive for hepatitis or not). The workflow includes data preprocessing, model training, hyperparameter tuning, and model evaluation with various models.

# Setup Instructions
Install the necessary dependencies, including PySpark, PyDrive, and OpenJDK.

Set up the Java environment variable.

Authenticate and create a PyDrive client to handle file operations on Google Drive.
# Data Processing
Load and preview the dataset to understand its structure.

Select the relevant columns and handle missing values by filling them with zeros.

Encode the categorical variables such as 'Sex' and 'Category' to numerical values.

Assemble the features into a single vector column to prepare the data for modeling.
# Model Training and Evaluation
Split the dataset into training and testing sets to evaluate the model's performance accurately.

Train a Logistic Regression model using cross-validation and hyperparameter tuning to find the best parameters.

Evaluate the Logistic Regression model on the test set and save the best model.
# Additional Models
Decision Tree:

Train and evaluate a Decision Tree model with cross-validation and hyperparameter tuning.

Save the best Decision Tree model and record its performance on the test set.

Random Forest:

Train and evaluate a Random Forest model with cross-validation and hyperparameter tuning.

Save the best Random Forest model and record its performance on the test set.
