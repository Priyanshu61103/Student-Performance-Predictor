# Student-Performance-Predictor

This project uses a machine learning model to predict whether a student will pass or fail based on various socio-economic and academic factors from the StudentsPerformance.csv dataset.

## Problem Statement
Predict if a student passes (average score ≥ 60) using features such as:
1. Gender
2. Race/Ethnicity
3. Parental level of education
4. Lunch type
5. Test preparation course
6. Math, Reading, and Writing scores

## Tech Stack
Language: Python
Libraries: pandas, numpy, scikit-learn, matplotlib
Model: Decision Tree Classifier

## Features & Workflow
1. Data Preprocessing
2. Label encoding of categorical features
3. Feature engineering: average score and pass/fail label
4. Model Training
5. Used Decision Tree Classifier from sklearn
6. Split into train-test sets (80-20)
7. Evaluation
8. Achieved 96% accuracy on test data
9. Insightful predictions based on socio-economic indicators

## Results
1. High model accuracy demonstrates strong correlation between parental education, test preparation, and student success.
2. Visualized feature impact and student distribution across various demographics.
