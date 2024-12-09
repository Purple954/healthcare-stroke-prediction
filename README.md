# healthcare-stroke-prediction
## Healthcare Stroke Prediction Model
# Overview
This project involves building a predictive model to classify whether a person has a stroke based on various healthcare and demographic factors. The dataset used is the Stroke Dataset, which includes various health metrics such as age, gender, smoking status, and medical history. The model is built using Random Forest Classifier and evaluated with metrics like accuracy and confusion matrix.

# Objective
Preprocess healthcare data to prepare it for machine learning.
Encode categorical variables using One-Hot Encoding.
Train a Random Forest model to predict stroke occurrence.
Evaluate the model's performance using accuracy, confusion matrix, and classification report.
Requirements
To run this project, you'll need the following Python libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn

# Dataset
The dataset used in this project is a CSV file named healthcare-dataset-stroke-data.csv, which contains various health-related attributes for each patient. The dataset includes the following columns:

id: Unique identifier for each record.
gender: Gender of the patient.
age: Age of the patient.
hypertension: Whether the patient has hypertension (1 = Yes, 0 = No).
heart_disease: Whether the patient has heart disease (1 = Yes, 0 = No).
ever_married: Whether the patient has ever been married.
work_type: The type of work the patient does.
Residence_type: Type of residence (Urban/Rural).
smoking_status: Smoking status of the patient.
stroke: Target variable indicating whether the patient had a stroke (1 = Yes, 0 = No).

# Conclusion
This project demonstrates how to build a predictive model using healthcare data to predict stroke occurrence. The model achieves an accuracy score that helps assess its performance, and further improvements can be made by tuning hyperparameters or trying different algorithms.

