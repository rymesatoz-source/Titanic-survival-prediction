Titanic - Machine Learning from Disaster
Project Overview
This project aims to predict the survival of passengers on the Titanic using various machine learning techniques. I have followed a complete end-to-end Machine Learning pipeline, from initial data exploration to training and evaluating different models. This project demonstrates my ability to handle a real-world classification problem.

Skills and Techniques Demonstrated
This repository is a testament to my proficiency in key data science and machine learning concepts:

1. Data Preprocessing & Cleaning
Missing Values: Handled missing data in the dataset, particularly in the Age and Embarked columns, using appropriate imputation techniques.

Categorical Data Handling: Converted non-numeric, text-based data (e.g., Sex, Embarked) into a numerical format suitable for machine learning models using One-Hot Encoding.

2. Feature Engineering
I created new, more informative features from the existing data to improve model performance:

Family_Size: A new feature to determine if a passenger was traveling alone or with their family.

Title: Extracted titles from passenger names to identify their social status, which is a strong predictor of survival.

3. Model Training & Evaluation
I trained and evaluated two classification models to compare their performance:

Logistic Regression

Random Forest

To thoroughly assess the models, I used multiple performance metrics beyond simple accuracy, including Precision, Recall, and F1-Score. The Random Forest model was chosen as the final model due to its superior performance across these metrics.

Repository Structure
Titanic - Machine Learning from Disaster.ipynb: The main Jupyter Notebook containing all the code for data analysis, cleaning, feature engineering, model training, and evaluation.

train.csv: The primary dataset used for training the model.

test.csv: The test dataset from Kaggle, for which predictions can be generated.

Technologies Used
Python

Pandas

Numpy

Scikit-learn

Matplotlib

Seaborn
