# Diabetes-Predicton-with-Machine-Learning

Link to Code: [Google_Colab_notebook](https://colab.research.google.com/drive/1mhgvwGl8QW8HXv8T4dADFeUJniKlQXf_?usp=sharing)
## Introduction
The prevalence of diabetes is a growing global concern, and early detection is crucial for effective management. Machine learning models can play a significant role in predicting diabetes risk based on clinical and demographic data. This project explores the application of machine learning to predict the onset of diabetes in the Pima Indian population using the well-known Pima Indians Diabetes Database.  

## Dataset Description
Data Source: [pima-indians-diabetes-database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
The Pima Indians Diabetes Database, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases, contains data for 768 female Pima Indians aged 21 years and older. The dataset includes the following features:  
  
**Pregnancies**: Total number of pregnancies.  
**Glucose**: Plasma glucose concentration measured after a two-hour oral glucose tolerance test.  
**Blood Pressure**: Diastolic blood pressure in millimeters of mercury (mm Hg).  
**Skin Thickness**: Triceps skin fold thickness in millimeters (mm).  
**Insulin**: Serum insulin level after two hours (mu U/ml).  
**BMI** (Body Mass Index): Weight in kilograms divided by the square of height in meters.  
**Diabetes Pedigree Function**: A function calculating an individual's risk of developing diabetes based on their family history.  
**Age**: Age in years.  
The target variable, "**Outcome**," is binary, where 1 indicates the patient has developed diabetes, and 0 indicates no diabetes.  

# Data Analysis

Data Cleaning and Exploration:  
The dataset was explored to understand its structure.  
To ensure data quality, missing values were handled appropriately.
Descriptive statistics, including the mean, mode, mininum, maximum, and standard deviation, were calculated for each feature to understand the data's central tendencies and dispersion.  
Visual representations, such as histograms and box plots, were used to explore the distribution of numerical features.
Pair plots and correlation matrices were employed to visualize the relationships between features and the target variable.  
  
Data Preprocessing: The dataset underwent standard scaling to normalize feature values. 
  
Model Training: Dataset was split into training and testing sets and trained the logistic regression model using the training data. 
  
Model Evaluation: The model's performance was assessed using metrics such as accuracy, precision, recall, F1 score, and the ROC AUC (Receiver Operating Characteristic Area Under the Curve).  
# Results
Our findings from the logistic regression model are as follows:  

Accuracy: 78%  
Precision: class 0 (no diabetes): 80%; class 1 (diabetes): 74%  
Recall: class 0: 89%; class 1: 57%  
F1 score: class 0: 84%; class 1: 64%  
ROC AUC score: 0.84  

These results demonstrate that logistic regression can be a valuable tool for diabetes prediction. However, further refinements are possible to improve the model's ability to correctly identify individuals with diabetes.
