CREDIT_SCORING CLASSIFICATION BY EMAN SARFRAZ

We developed a credit scoring model using the following steps:

Data Loading: Loaded the dataset from a CSV file.
Synthetic Target Creation: Created a synthetic 'Creditworth' column with 'Good' and 'Bad' values for demonstration.
Feature and Target Separation: Separated features and the target variable ('Creditworth').
Preprocessing:
Numerical features: Imputation and standardization.
Categorical features: Imputation and one-hot encoding.
Data Splitting: Split the data into training and test sets.
Model Training: Used a pipeline to preprocess the data and train a Random Forest classifier.
Predictions: Made predictions on the test data.
Model Evaluation: Evaluated the model using accuracy, precision, recall, and F1-score.
Classifier Used: Random Forest
We used a Random Forest classifier, an ensemble method that builds multiple decision trees and averages their predictions. It is robust, handles mixed data types well, and provides feature importance insights.






