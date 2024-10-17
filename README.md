# Project Overview
This project is about building a Health Prediction App that uses machine learning to predict diseases based on symptoms entered by the user. The process involves preparing the data, training different machine learning models, testing how well they work, and using the best model to make predictions.

## Features

**Disease Prediction:** The app uses multiple machine learning models (Support Vector Machine, Gaussian Naive Bayes, Random Forest Classifier) to analyze symptoms and provide a possible diagnosis.

**Symptom Encoding:** The app converts symptom descriptions into a format that can be processed by the machine learning models.

**Ensemble Prediction:** The final diagnosis is determined by taking the most common prediction from all models, ensuring higher accuracy.

**User-Friendly Interface:** The system is accessible through a mobile app or web platform, making it easy to use in various settings (hospitals, telemedicine, or individual use).

## Machine Learning Models Used

1) Support Vector Machine (SVM)

2) Gaussian Naive Bayes

3) Random Forest Classifier

These models are trained, tested, and evaluated for accuracy. We use cross-validation and confusion matrices to assess model performance.

## Data Preprocessing

The dataset is loaded from a CSV file, and missing values are handled by dropping columns.

Label encoding is applied to convert disease labels into numerical values.

The dataset is split into 80% training and 20% testing sets for model evaluation.

## Final Prediction

The app provides predictions from each model, and the final prediction is based on the majority result of the three models.

## How to Use

Input symptoms separated by commas (e.g., "fever, headache").

The app encodes the symptoms and runs them through the models.

The app displays the predictions from each model and the final combined diagnosis.

## Business Model

The app operates on a subscription and pay-per-use model:

**Individual Subscription:** Users can subscribe monthly or annually for unlimited disease predictions.

**Institutional Subscription:** Hospitals or clinics can subscribe to integrate the app into their diagnostic processes.

**Pay-Per-Use:** For occasional users, the app offers one-time predictions at a fixed cost.

## Future Enhancements

Add more machine learning models for better accuracy.

Expand the database to include more diseases and symptoms.

Implement real-time updates for symptoms and medical conditions.
