SpaceX Falcon 9 First Stage Landing Prediction
==============================================
 Project Overview
==================

SpaceX advertises Falcon 9 rocket launches at a significantly lower cost (~$62 million) compared to other providers (>$165 million). A major reason for this cost reduction is reusability of the first stage booster.

This project builds a machine learning pipeline to predict whether the first stage of a Falcon 9 rocket will successfully land after launch. Predicting landing success helps estimate launch costs and enables competitor companies to make informed bidding decisions.

This project is part of the IBM Data Science Professional Certificate (Coursera) – Capstone Project.


 Objective
 =========

Predict whether the Falcon 9 first stage will land successfully

Analyze historical SpaceX launch data

Build and evaluate multiple machine learning models

Identify the best-performing model for landing prediction


 Dataset
 =======

The dataset was collected from:

SpaceX API

Wikipedia Falcon 9 Launch Records

Features include:

Launch site

Orbit type

Payload mass

Number of engines

Booster version


Machine Learning Pipeline
=========================

The project follows a complete data science workflow:

1️⃣ Data Collection (API + Web Scraping)

2️⃣ Data Wrangling & Cleaning

3️⃣ Exploratory Data Analysis (EDA)

4️⃣ Feature Engineering

5️⃣ Data Visualization

6️⃣ Model Building

7️⃣ Model Evaluation & Comparison


 Models Used
 ===========

Logistic Regression

Support Vector Machine (SVM)

Decision Tree Classifier

K-Nearest Neighbors (KNN)

Evaluation Metrics
==================

Accuracy

Confusion Matrix

Cross-validation score

Launch outcome

Landing outcome (target variable)

Results
=======
Multiple classification models—including Logistic Regression, KNN, Decision Tree, and SVM—were trained with hyperparameter tuning using GridSearchCV and 10-fold cross-validation to predict Falcon 9 first-stage landing success. All models showed similar accuracy due to the small dataset and strong, near-linearly separable features, highlighting the robustness of the feature engineering and preprocessing steps.


