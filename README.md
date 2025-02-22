Medical Data Analytics Projects Repository

Welcome to the Medical Data Analytics Projects Repository. This repository showcases a collection of data-driven healthcare projects focused on using machine learning, deep learning, and statistical analysis to gain insights into critical medical conditions.
Each project is built upon real-world medical datasets and highlights the power of data science in advancing healthcare research.

Projects Overview

1. Cost vs. Outcome Analysis in Hospitals

Objective: Analyze the relationship between hospital costs and patient outcomes to identify trends and inefficiencies.

Data: Real-world hospital data including:

Patient demographics: Age, Gender

Medical history: Diagnoses, Treatment plans

Financial data: Treatment costs, Length of stay

Outcomes: Recovery rates, Readmission rates

Methodology:

Data cleaning and preprocessing

Statistical analysis to identify cost-outcome correlations

Visualization of key trends (cost vs. recovery time, cost vs. readmission rates)

Insights: Aimed to uncover how healthcare spending impacts patient outcomes, guiding data-driven decisions for cost-effective treatments.

2. Deep Learning-Based Cardiovascular Disease Prediction

Objective: Predict whether a person has cardiovascular disease (binary classification: cardio = 0 or 1).

Data: Sourced from Kaggle, containing patient health metrics:

Demographics: Age, Gender

Physical stats: Height, Weight

Medical factors: Systolic & Diastolic Blood Pressure, Cholesterol, Glucose levels

Lifestyle: Smoking, Alcohol consumption, Physical activity

Model: Feedforward Neural Network (ANN)

Hidden Layers: 2 (64 & 32 neurons, ReLU activation)

Dropout layers for regularization

Sigmoid activation in output layer

Optimizer: Adam

Loss: Binary Cross-Entropy

Results: Achieved a test accuracy of 73.91%.

3. Prediction of Sepsis from Clinical Data

Objective: Develop a machine learning model to predict sepsis — a life-threatening response to infection.

Data: Kaggle’s “Prediction of Sepsis” dataset, containing clinical variables:

Vital signs: Heart Rate (HR), Oxygen Saturation (O2Sat), Temperature (Temp)

Blood Pressure: Systolic (SBP), Mean Arterial Pressure (MAP), Diastolic (DBP)

Data Preprocessing:

Mean imputation for numerical features

Mode imputation for categorical features

Median imputation for outliers

Models:

Random Forest Classifier: Accuracy = 98.37%

Gradient Boosting Classifier: Accuracy = 98.22%

4. Correlating Gut Microbiome Composition with Obesity and Type 2 Diabetes

Objective: Explore statistical relationships between gut microbiome composition and metabolic health indicators (BMI, HbA1c).

Data:

Microbiome dataset: Kaggle

Obesity to HbA1c dataset: Zenodo

Datasets merged for comprehensive analysis

Data Preprocessing:

Dropped missing values

Converted categorical microbiome data into dummy variables

Statistical Analysis:

Parametric tests: Pearson Correlation, T-test, ANOVA, Linear Regression

Non-parametric tests: Spearman Correlation, Mann-Whitney U Test, Kruskal-Wallis Test, Kendall’s Tau

Results: Provided statistical evidence linking gut microbiome composition to obesity and Type 2 diabetes.

About This Repository

This repository aims to bridge the gap between medical science and data analytics by leveraging real-world medical data to build predictive models and uncover meaningful insights. Each project involves careful data collection,
preprocessing, model training, and result interpretation — all tailored to healthcare challenges.

Feel free to explore the projects, dive into the code, and contribute if you'd like to enhance these models or add new healthcare analytics projects.
