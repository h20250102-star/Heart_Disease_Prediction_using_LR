# Heart_Disease_Prediction_using_LR
The World Health Organization reports that cardiovascular diseases cause millions of deaths each year worldwide. Early detection of heart disease risk can help guide preventive measures and lifestyle changes. This study aims to identify key risk factors and predict heart disease using logistic regression.
Solution Overview

The objective of this study is to classify whether a patient is at risk of developing coronary heart disease (CHD) within the next 10 years. A Logistic Regression model is used to perform this binary classification task.

About Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification problems. It estimates the probability of a categorical outcome based on one or more input features. It is widely used for binary classification (e.g., disease vs no disease) and can also be extended to multi-class problems.

Dataset Description

The dataset is obtained from the Kaggle platform and is based on the Framingham Heart Study, which tracks cardiovascular health in residents of Framingham, Massachusetts.
It contains 4,000+ records with 15 attributes describing patient health and lifestyle.

Features in the Dataset
1. Demographic Information
Sex – Male or Female
Age – Age of the patient
Education – Education level (1–4 scale)
2. Behavioral Factors
Current Smoker – Smoking status
Cigarettes per Day – Daily cigarette consumption
3. Medical History
BP Medications – On blood pressure medication or not
Prevalent Stroke – History of stroke
Prevalent Hypertension – Hypertension status
Diabetes – Diabetic or not
4. Clinical Measurements
Total Cholesterol (totChol)
Systolic BP (sysBP)
Diastolic BP (diaBP)
BMI – Body Mass Index
Heart Rate
Glucose Level
Target Variable
TenYearCHD – Indicates 10-year risk of CHD (1 = Yes, 0 = No)
Tools and Libraries Used
Pandas – Data handling
Matplotlib & Seaborn – Data visualization
Scikit-learn – Model building and evaluation
Workflow / Methodology
1. Data Preparation
Import dataset
Handle missing values
Perform preprocessing
2. Exploratory Data Analysis (EDA)
Visualizations (count plots, pair plots)
Correlation analysis
3. Model Development
Separate features (X) and target (y)
Split data into training and testing sets
Train Logistic Regression model
4. Model Evaluation
Accuracy Score
Confusion Matrix
Classification Report
5. Visualization
Plot confusion matrix
Analyze model performance
