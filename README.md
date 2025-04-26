# Deployment-Project-on-Pima-Indians-Diabetes-Prediction
Developed a diabetes prediction model (Logistic Regression) achieving 79.65% accuracy on a Pima Indians dataset (768 samples, 8 clinical features) and deployed it via Flask with real-time form validation and probability-based risk assessment.


A machine learning-powered web application that predicts diabetes risk using the Pima Indians Diabetes Dataset. The system leverages Logistic Regression (79.65% test accuracy) trained on 768 clinical samples with 8 diagnostic parameters including glucose levels, BMI, and age. Features include:

Technical Implementation

ML Pipeline: Scikit-learn implementation with train-test splitting (70-30 ratio) and class imbalance analysis

Model Performance: Confusion matrix visualization (133/150 correct non-diabetic predictions, 51/81 diabetic) and classification metrics (0.75 precision/0.63 recall for positive class)

Web Deployment: Flask API with HTML form interface handling 8 clinical parameters

Model Persistence: Pickle serialization for production-ready model serving

Key Features

Real-time risk assessment with probability confidence scoring

Input validation for clinical parameters (min/max constraints based on dataset statistics)

Responsive interface with result visualization

Error handling for invalid/non-numeric inputs


This production-ready implementation demonstrates end-to-end ML deployment capabilities from exploratory analysis to web integration.
