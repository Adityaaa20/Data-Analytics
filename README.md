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

5. AI-Based Early Prediction of Non-Communicable Diseases (NCDs)

Data Overview

Training Data Shape: (81412, 48)

Testing Data Shape: (20354, 48)

Model Performance

Model Accuracy: 91% (0.91)

Classification Report

              precision    recall  f1-score   support

           0       0.00      0.00      0.00       821
           1       0.91      1.00      0.95     18586
           2       0.50      0.00      0.00       947

    accuracy                           0.91     20354
   macro avg       0.47      0.33      0.32     20354
weighted avg       0.86      0.91      0.87     20354

The model performs significantly better for class 1 compared to class 0 and class 2. This indicates a bias towards class 1, suggesting that class 1 dominates the dataset.

Confusion Matrix Explanation

True Positives (TP): Correctly predicted positive class (e.g., predicted "1" when actual was "1").

True Negatives (TN): Correctly predicted negative class (e.g., predicted "0" when actual was "0").

False Positives (FP): Incorrectly predicted positive class (e.g., predicted "1" when actual was "0").

False Negatives (FN): Incorrectly predicted negative class (e.g., predicted "0" when actual was "1").

Regression Metrics

Mean Absolute Error (MAE): 26.92

Mean Squared Error (MSE): 984.19

Root Mean Squared Error (RMSE): 31.37

R-Squared (R²): 0.0454

6. Machine Learning for Identifying Socioeconomic Risk Factors of NCDs

Model Performance

Model Accuracy: 89% (0.89)

Classification Report

              precision    recall  f1-score   support

           0       0.95      0.90      0.92       325
           1       0.93      0.92      0.93       131
           2       0.90      0.83      0.86       257
           3       0.81      0.90      0.85       279

    accuracy                           0.89       992
   macro avg       0.89      0.89      0.89       992
weighted avg       0.89      0.89      0.89       992

The model shows strong predictive performance with an overall accuracy of 89%. It effectively distinguishes income groups, especially high-income and upper-middle-income categories, with minimal misclassification between non-adjacent groups.

Insights

High and upper-middle-income countries are classified reliably.

Factors like life expectancy, healthcare expenditure, and education play a significant role in boosting model performance.

Application

The model helps policymakers identify risk factors contributing to Non-Communicable Diseases (NCDs) based on income classification, allowing for targeted interventions to mitigate health disparities.

7. AI-Driven Epidemiological Modeling for NCD Trends

Model Performance

Model Accuracy: 89% (0.89)

Classification Report

              precision    recall  f1-score   support

           0       0.95      0.90      0.92       325
           1       0.93      0.92      0.93       131
           2       0.90      0.83      0.86       257
           3       0.81      0.90      0.85       279

    accuracy                           0.89       992
   macro avg       0.89      0.89      0.89       992
weighted avg       0.89      0.89      0.89       992

The confusion matrix provides insights into the model's classification of income groups based on socioeconomic and health-related factors. The model effectively distinguishes high-income and upper-middle-income countries with minimal misclassification between non-adjacent categories.

Insights

Strong predictive performance across income groups.

High reliability in classifying high and upper-middle-income countries.

Factors like life expectancy, healthcare expenditure, and education enhance model accuracy.

Application

The project highlights how AI models can forecast NCD trends by analyzing socioeconomic indicators. This approach supports policymakers in developing data-driven strategies to mitigate the risk factors contributing to NCDs.
